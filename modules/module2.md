# 2) Measurement Strategies, Basics of the Snowpack Mass and Energy Balances, and Snowpack Dynamics 

# Background

For many regions, mountain snow provides much of society's water.  The weight of snow is due almost entirely to its water content.  Therefore, one of the main instruments of snow hydrology is a giant scale similar to the one you might find in your bathroom.  Many snow pillows are filled with fluid and measure the pressure on the fluid from the weight of the snow. Other snow pillows are "fluid-less" and work similarly to a standard bathroom scale. In the Western U.S., networks of snow pillows are maintained by the [National Resource Conservations Service,NRCS](https://www.nrcs.usda.gov/wps/portal/wcc/home/quicklinks/imap) and the [California Department of Water Resources](https://cdec.water.ca.gov/snow/).

[![Watch a video of a fluidless snow pillow being installed in Colorado](https://img.youtube.com/vi/6Ivn666w5xo/default.jpg)](https://www.youtube.com/watch?v=6Ivn666w5xo)

Click on the photo above to see a short Youtube video of a snow pillow being installed at Kettle ponds in the East River Basin. Look at the map below to see where these snow pillows are located relative to the meteorological towers at Kettle Ponds.

![Here is a map of where the Kettle Ponds pillows are located](data/KettlePondsPillowlidarmap.png)

Above, we see an aerial photo, with each tower and corresponding snow pillow labeled.  We also see a lidar map of snow depth, with the snow pillow locations shown with circles, and a webcam photo taken from the downwind tower towards the central and upwind towers. This map will be useful in the lab and homework below, and in future modules.

---

```note
## Lab 2: Mass Balance

In Lab 2, we will look at data from SNOTEL stations and the Kettle Ponds field site, in the Upper East River Valley. 

We will download SNOTEL data and use pre-downloaded SOS data. 

Working through labs 2-1, 2-2, and 2-3 will prepare you to complete Homework 2. 

* [Lab 2-1](lab2/lab2-1.ipynb)
* [Lab 2-2](lab2/lab2-2.ipynb)
* [Lab 2-3](lab2/lab2-3.ipynb)
* [SoS dataset](data/sos_full_dataset_30min.nc)
* [Precipitation dataset](data/kettle_ponds_precip.csv)
```

---

## Homework 2

### Problem 1

Using the observations of precipitation and the snow pillow data at Kettle Ponds and the two SNOTEL stations (see Module 2 labs), we are going to investigate the mass balance and snow accumulation at sites in the East River Valley.

A. Plot a timeseries of total accumulated precipitation and total accumulated snow water equivalent from the four snow pillows.  Add to your two plots timeseries data from the two Snotel Stations located nearby.

B. Calculate the seasonal maximum SWE from one of the Kettle Ponds (not Snotel) snow pillows. Calculate the cumulative precipitation up until the date of your identified maximum SWE. Calculate the percentage of the cumulative precipitation accounted for by the max SWE value.

C. Write out the snow mass balance equation from lecture.  Given your calculations for part B, what terms in the mass balance do you think are most likely to account for the disparity between cumulative precipitation and maximum SWE? How certain do you think our estimates of cumulative precipitation and maximum SWE are?

D. Discuss which factors of the mass balance are most likely to be vary spatially Reference your plots from A.  Is there more variability between sites further away?  Or are the four snow pillows at Kettle Ponds as different as the two SNOTEL sites from elsewhere in the watershed?

E. Summer researchers at the Rocky Mountain National Biological Lab in the Upper East River Valley want to start their research as soon as possible. To access the lab, they need to drive down a forest service road that is currently snowed in.  The forest service opens the road when the snow melts and disappears. Using the long term records at the SNOTEL sites, and (optionally) any other information you like, predict when the snow will be gone (and the road clear) in 2025.

F. Following lab 2-3, calculate snow density at one Kettle Ponds tower using 30-minute data (i.e. mimic what we did in lab 2-3, but do not resample the data to daily time steps). For the time period January 1-15, 2023, plot snow density and snow depth. Explain what patterns you see in the two time series.

G. In snow models, a simple exponential decay equation is used to predict the compaction of snow over time (e.g. Essery et al., 2013, https://www.sciencedirect.com/science/article/abs/pii/S0309170812002011). Such a model takes the form:
```
density = max_density + (initial_density - max_density)*e^(-1 / tau_p)
```
where max_density is the maximum possible snow density (e.g. 300-400 kg/m^3), initial_density is the starting density of the snowpack, and tau_p is a decay constant, e.g. 3.6e5. 
Identify a short time period between January 1--15 during which you observe a single instant of decaying density/snow depth (should be between 12 and 48 hours long).
Apply this equation to the short time series of snow density.
Plot the observed density and the predicted density time series.

### Problem 2
On your reading of Lundquist et al. 2024 “Sublimation of Snow””.

In Figure 3B, SWE measured on four different snow pillows show significant and diverging change on the morning of December 22. 
What caused the SWE signals to diverge? 
Based on this answer, what do you think is a shortcoming of SNOTEL measurement sites?
Describe the ideal area for a SNOTEL site (think about topography, weather/wind conditions).
Maximum 8 sentences. 


## Additional resources  
Kelly Elder put together a good set of training videos for the NASA SnowEx Campaigns.  You can view these via the links below.
* [An Introduction to NASA SnowEx Snow Pit Sampling Methods](https://www.youtube.com/embed/PCteYh66dEQ)
* [SnowEx Snow Pit Profile Sampling](https://www.youtube.com/embed/DEJvh5dZnpY)
* [SnowEx Snow Pit Density Sampling](https://www.youtube.com/embed/VtHj3ccu5A8)

This website on Snow Metamorphism includes some intuitive explanations.
[SLF Website on Snow Metamorphism](https://www.slf.ch/en/snow/snow-as-a-material/snow-metamorphism.html)
