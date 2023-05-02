# 5) Radiation, albedo, and the energy balance


# Background
![Photo of April 2023 dust event at Kettle Ponds](data/Dust_on_SOS.png)

[News about the dust on snow event](https://crestedbuttenews.com/2023/04/quicker-spring-runoff-expected-with-recent-dust-storm-impact/)

For background on the earth's energy balance as a whole, NCAR has put together this [4-minute video](https://www.youtube.com/watch?v=t9B8gGQtJzo).  If you prefer reading to a video, they also have this [online resource on the total energy balance](https://scied.ucar.edu/learning-zone/how-climate-works/energy-budget).  

The [Snow International, SINTER](https://nsidc.org/sinter) community puts on snow schools and lectures to help people worldwide learn more about snow science and current snow research.  From the 2021 online snow school series, you can watch the [SINTER Lecture by Cassie Lumbrazo on the Energy Balance.](https://youtu.be/LV5elFtjjcc) 

 ```Key Points
The majority of the energy available for snow melt or sublimation comes from the net radiation, which is a balance of incoming shortwave, reflected shortwave, incoming longwave, and emitted longwave radiation.

* Radition comes in a wide range of frequencies and wavelengths, which interact with molecules and materials in different ways. 
* Shortwave (SW) radiation comes from the sun and is a function of time of year, time of day, cloud cover, atmospheric aerosols, and topographic position. We can predict/model potential SW radiation well. **Geometry matters.**
* In general, the atmosphere allows SW radiation to pass through it, with the exception of greenhouse gases, which absorb SW radiation and re-emit it as longwave (LW) radiation.  Water vapor is the most important greenhouse gas in the earth's atmosphere, followed by carbon dioxide. **Clouds matter.** 
* Snow is highly reflective, returning 60-90% of the incoming SW radiation to the atmosphere. This means that snow has a high [albedo](https://mynasadata.larc.nasa.gov/mini-lessonactivity/what-albedo). 
* Snow's surface temperature changes rapidly as it absorbs and loses energy.  This temperature controls how much longwave radiation snow emits.  Snow has a high [emissivity](https://www.jpl.nasa.gov/images/pia18833-nasa-spacecraft-maps-earths-global-emissivity), which means that it absorbs most of the incoming LW radiation, reflecting very little.
```

In cooperation with our campaign, NOAA is conducting the [Study of Precipitation, the Lower Atmosphere and Surface for Hydrometeorology, SPLASH, campaign](https://psl.noaa.gov/splash/). From the prior link, if you click on _data_ and on _KettlePonds_, you can see photos of the radiometer and streams of data.  For today's lab, we will bring in one of the [Superheros of SPLASH](https://storymaps.arcgis.com/stories/093640ac6bdc479394d7fd9c7068fd27) to help us with our investigation.

```note
## Lab 5: Plotting radiation data around the snow.

Download the lab and data files to your computer. Then, upload them to your JupyterHub [following the instructions here](/resources/b-learning-jupyter.html#working-with-files-on-our-jupyterhub).

* [Lab 5-1: Plotting Radiation Data at Kettle Ponds and Potential Radiation](lab5/lab5-1.ipynb)
* [SPLASH radsys_attribute data, used in lab5-1](data/radsys_attributes.txt)

```

## Homework 5

### Problem 1: Comparing solar radiation sensors

A common problem in mountain snow energy balance studies is that snow accumulates on the upward pointing radiometers.  Find a time in our dataset when you think this occurred and explain your reasoning. _Hint, you may want to look at the precipitation dataset in Lab 2 for timing._ Which radiometer set-up (SOS or SPLASH) worked better during your timeperiod?  Why do you think this is?  Compare downwelling and reflected shortwave radiation with potential shortwave radiation for your day.
 
 ```tip
Former UW PhD student Karl Lapo created several GitHub repositories for working with radiation data in mountain areas and a paper about identifying times when sensors have radiation on them.

* [Paper on identifying period with snow on a radiometer](https://doi.org/10.1002/2015WR017590)
* [Mountain observation quality control](https://github.com/klapo/moq)
```

### Problem 2: Clouds
 
Identify a period of variable cloud cover in the dataset.  Explain how you can use both shortwave and longwave measurements to identify variations in clouds.  include periods from both day and nighttime hours.  How are the shortwave and longwave datasets complimentary?  Do they tell you the same or different information about the clouds?  


### Problem 3: Dust on snow and albedo
 
We know that the reflectivity of snow, termed albedo, calculated as outgoing-solar-radiation divided by incoming-solar-radiation, is brightest right after new snowfall and then darkens as snow ages.  This occurs both as a process of snow grains rounding and growing and as snow gets dirtier with deposition.  In early April, a substantial amount of dust was deposited on our site at Kettle Ponds (see the photo at the top of this page).  Using the Kettle Ponds radiation dataset, investigate how albedo changes both with time after a new snowfall event earlier in the winter (no dust) and in mid-April (with dust).  How much does dust impact albedo compared to the natural snow aging process? 
