# 8) Snow-dominated watershed hydrology

For this module, we will model snow processes across the entire upper East River Valley.
![distributed modeling image](../modules/data/module8_webpage_image.png)

```note
* [Lab 8-1](lab8/lab8-1.ipynb) - Predicting streamflow with the SWE-regression method
* [Lab 8-2](lab8/lab8-2.ipynb) - Predicting melt rate and streamflow with a distributed model
* [SoS dataset](data/sos_full_dataset_30min.nc)
* [openAMUNDSEN Inputs](data/openamundsen.zip)
* [openAMUNDSEN Configuration File](lab8/open_amundsen_config.yml)
```

## Homework 7/8
On Thursday March 6th, we will hold a discussion on the paper linked below.
Please read the paper, take notes, and prepare some discussion points.

[Li et al., 2017, How much runoff originates as snow in the western United States, and how will that change in the future?](https://agupubs.onlinelibrary.wiley.com/doi/10.1002/2017GL073551)

**Problem 1 - Temperature-Index Method**
For this problem, we will use the Temperature-Index method for predicting snow melt, discussed in Module 7 and introduced in Lab 7-3.

a. Calculate M<sub>f</sub> using measurements from the Schofield Pass Snotel station and report your value. I.E. mimic Lab 7-3 but for measurements from a different Snotel station. Use the same date range, 1990-2024. Note that we downloaded and used Schofield pass data in Lab 2-1. 

b. Compare M<sub>f</sub> values calculated at the Butte and Schofield Pass Snotel stations. Explain why you think one is larger/smaller than the other.

c. Choose an M<sub>f</sub> value calculated from either the Butte or Schofield Pass Snotel stations, and model snowpack ablation at Kettle Ponds. I.E. mimic the second half of Lab 7-3 where we modeled snowpack ablation for the Butte Snotel station, but model snowpack ablation at Kettle Ponds using air temperature measurements at Kettle Ponds. Your solution to this problem should include:
  * A statement of which M<sub>f</sub> value you selected to model snowpack ablation at Kettle Ponds, and why.
  * A plot of modeled and measured SWE during the ablation period (April 1 - June 1) (I.E. create a similar plot to the final plot generated in Lab 7-3).

d. Explain why you think modeled and measured ablation from part c disagree. What do you know happened during the 2024 ablation period and how are those represented or not represented in the degree day factor, M<sub>f</sub>.

e. We know that the melting of the snowpack is a result of the (snowpack energy balance)[modules/module4.md]. Explain, for each term in the energy balance equation, if and how the temperature-index method incorporates the influence of that energy flux term. Here's one part of the answer that you can use as a model for your response: The ground heat flux is not really represented in the temperature-index method, because the air temperature and the ground heat flux are not related. First of all, the ground heat flux out of the earth is approximately constant, Second, snow is a great insulator, so ground heat flux is unlikely to impact air temperature. Therefore, air temperature does not incorporate the influence of the ground heat flux on snowpack melt.

**Problem 2 - Distributed Modeling - Explaining the results of Lab 8-2**

a. Lab 8-2 demonstrated that the model of the snowpack in the upper East River Valley melted out about three weeks later than the actual snowpack at Kettle Ponds. Explain, using the two plots generated in Lab 8-2 (modeled vs. measured SWE and modeled vs. measured energy balance), why you think the modeled snowpack melted out later than the measured snowpack. 

b. Lab 8-2 demonstrated how the timing of snowmelt propagated throughout the basin (see the 2x2 grid of snow melt plots towards the end of the lab). Explain how the spatial distribution of melt rates propagates throughout the basin, making sure to include the details of where melt starts first and why, and where it happens last and why. Explain why this spatial-temporal relationship exists. 

**Problem 3 - Distributed Modeling - Running experiments with the model: Rain-on-snow event vs [Hot-Wind event](https://youtu.be/8CBCsRZfNDs?si=MOyu350mbcknx90c)**

For this problem, you will modify the inputs to the model twice, and rerun the model twice. You will then compare the three different sets of model results - the first set of model results is generated in Lab 8-2; you will generate the second and third sets of model results.

Model experiment 1 - Hot-wind Event: 
* Modify your inputs in the following way: between 2023-05-28 and 2023-05-29 (including all hours from both days), set the temperature column to a constant +15˚C (288.15 K, note the inputs are in units of Kelvin) and the wind speed column to a constant 10 m/s.

Model experiment 2 - Rain-on-snow Event: 
* Modify your inputs in the following way: between 2023-05-28 and 2023-05-29 (including all hours from both days), set the temperature column to a constant +15˚C (288.15 K, note the inputs are in units of Kelvin) and the precip column to a constant 10.

You can modify the model inputs by directly editing the csv file (the inputs are in the file `1.csv`), or you can use pandas to read in the csv, modify it, and rewrite the csv to disc. 

I recommend the following steps for modifying inputs and saving model results:
1. Run the model as we did for Lab 8-2.
2. When the model runs, a directory `open_amundsen_results` will be created automatically. Rename this directory to something else. I recommend a name that indicates these results are with the "actual/original" inputs. 
3. Modify the `1.csv` file according to the instructions above for one of the model experiments.
4. Rerun the model, then rename the newly created `open_amundsen_results` directory. I recommend a name that indicates these are results associated with whichever model experiment you ran first.
5. Modify the `1.csv` file according to the instructions above for remaining model experiment.
6. Rerun the model, then rename the newly created `open_amundsen_results` directory. I recommend a name that indicates these are results associated with whichever model experiment you ran second.
  
Once you have three unique sets of model results, you can begin answering the following homework questions:

a. Create a plot of modeled SWE from each of the three model results (original model run, the "warm rain" model results", and the "warm wind" model results) for the whole season. Your plot should include three lines (you don't need to add measured SWE, although you can if you like). 

b. Explain how the SWE estimates differ. Explain how the "warm rain" and the "warm wind" event affected the snowpack melt-out differently/similarly and if these results are consistent with your expectations.

c. Create three plots, one plot using model results for each model run, that include energy balance terms for the time period May 25 - May 31. Include the following energy balance terms: Net radiation, sensible heat flux, latent heat flux, and precipitation energy flux. Note we created a plot including these terms in Lab 8-2.

d. Explain how the energy balances differ across the three model runs, particularly during the time period when you modified inputs (May 28 - 30). Make sure to include a discussion of: 1) Which energy balance terms are most important in each of the three model runs and 2) What these model experiments tell you about rain-on-snow events.

e. During a rain-on-snow event, which could theoretically include high winds, high air temperatures, and rainfall, what energy terms cause snow melt?