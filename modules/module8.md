# 8) Snow-dominated watershed hydrology

For this module, we will model snow processes across the entire upper East River Valley.
![distributed modeling image](../modules/data/module8_webpage_image.png)

```note
* [Lab 8-1](lab8/lab8-1.ipynb) - Predicting streamflow with the SWE-regression method
* [Lab 8-2](lab8/lab8-2.ipynb) - Predicting melt rate and streamflow with a distributed model
* [SoS dataset](data/sos_full_dataset_30min.nc)
* [Precipitation dataset](data/kettle_ponds_precip.csv)
```

## Homework 7/8
**Problem 1 - Temperature-Index Method**
For this problem, we will use the Temperature-Index method for predicting snow melt, discussed in Module 7 and introduced in Lab 7-3.

a. Calculate M<sub>f</sub> using measurements from the Schofield Pass Snotel station and report your value. I.E. mimic Lab 7-3 but for measurements from a different Snotel station. Use the same date range, 1990-2024. Note that we downloaded and used Schofield pass data in Lab 2-1. 

b. Compare M<sub>f</sub> values calculated at the Butte and Schofield Pass Snotel stations. Explain why you think one is larger/smaller than the other.

c. Choose an M<sub>f</sub> value calculated from either the Butte or Schofield Pass Snotel stations, and model snowpack ablation at Kettle Ponds. I.E. mimic the second half of Lab 7-3 where we modeled snowpack ablation for the Butte Snotel station, but model snowpack ablation at Kettle Ponds using air temperature measurements at Kettle Ponds. Your solution to this problem should include:
  * A statement of which M<sub>f</sub> value you selected to model snowpack ablation at Kettle Ponds, and why.
  * A plot of modeled and measured SWE during the ablation period (April 1 - June 1) (I.E. create a similar plot to the final plot generated in Lab 7-3).

d. Explain why you think modeled and measured ablation from part c disagree. What do you know happened during the 2024 ablation period and how are those represented or not represented in the degree day factor, M<sub>f</sub>.

e. We know that the melting of the snowpack is a result of the (snowpack energy balance)[modules/module4.md]. Explain, for each term in the energy balance equation, how the temperature-index method does or does not incorporate the influence of that energy flux term. Here's one part of the answer that you can skip: The ground heat flux is not really represented in the temperature-index method, because the air temperature and the ground heat flux are not related. The ground heat flux out of the earth is approximately constant, and the snowpack is a great insulator, so ground heat flux is not likely to impact air temperature, and therefore air temperature does not incorporate the influence of the ground heat flux on snowpack melt.

**Problem 2 - Regression Analysis**
Expand lab8-1 to be a *multiple* linear regression using multiple sites

**Problem 3 - Distributed Modeling**
Model experiments:
a. Modifying representation of snow layers - impacts on snow surface temperature, snow melt rates
b. Rain on snow event vs [Hot Wind Event](https://youtu.be/8CBCsRZfNDs?si=MOyu350mbcknx90c) - impacts on snow melt rate 
c. Accuracy of Streamflow