# 7) Turbulent transfer above the snow
Fluxes of sensible and latent heat above the snow.  For a good introductory text, we recommend [Terrestrial Hydrometeorology](https://bcs.wiley.com/he-bcs/Books?action=index&bcsId=6961&itemId=0470659378) by W. James Shuttleworth.  In particular, Chapter 2 on water vapor in the atmosphere, Ch 3 on vertical gradients in the atmosphere, and Chapters 15-19 on turbulence are helpful with this week's lessons.  If you don't have access to the text book, you may be interested in [U. Hawaii online text on water vapor](http://pressbooks-dev.oer.hawaii.edu/atmo/chapter/chapter-4-water-vapor/) and on [atmospheric stability](http://pressbooks-dev.oer.hawaii.edu/atmo/chapter/chapter-5-atmospheric-stability/) and Penn State online text on the [boundary layer](https://www.e-education.psu.edu/meteo300/node/697). 



# Background
[![Watch a video of Steve Oncley talking about how sonic anemometers work](https://img.youtube.com/vi/2kUJari_PpM/0.jpg)](https://www.youtube.com/watch?v=2kUJari_PpM)

Click on the photo above to hear Steve Oncley explain how the sonic anemometers work.  This week we will be using data from these sensors to study turbulent transfer or heat, moisture, and momentum.

Michi Haugeneder of SLF in Switzerland is collaborating on our project and has worked on novel ways to [visualize turbulence over snow](https://link.springer.com/article/10.1007/s10546-022-00752-3).  You can click [here](https://www.youtube.com/watch?v=pEcRLSMFXcw) to watch a brief video of Michi    explaining how we visualize turbulence with an IR camera and a sheet at the Kettle Ponds site.

```note
## Lab 7: Turbulence and the mass and energy balance

Download the lab and data files to your computer. Then, upload them to your JupyterHub [following the instructions here](/resources/b-learning-jupyter.html#working-with-files-on-our-jupyterhub).

* [Lab 7-1: Calculating atmospheric stability, the Richardson Number, and plotting turbulence data](lab7/lab7-1.ipynb) 
* All of the good stuff is in one lab this time, but Problem 2 will require info from prior labs and homework.

```

## Homework 7

### Problem 1: Do Stable Atmospheric Conditions Shut Down Turbulence?   
Most of us have seen buoyancy-driven convective plumes when heating from below causes a fluid to rise, but snow is generally colder than the air above.  When temperature increases with height, we say the atmosphere is stable.  Lab 7-1 walks you through how to convert our temperature measurements into virtual potential temperatures, which correct for density adjustments due to changes in pressure with elevation and due to different moisture contents.  With these corrections, we can assess the stability of the atmosphere above the snow surface.  Pick three different periods of 3-5 days in our dataset.  For each, assess the stability, the winds, the Richardson number, and the turbulent fluxes (TKE and sensible and latent heat fluxes, at two or more different heights).  How are these related?  What are the highest turbulent fluxes you observe during a period considered "strongly stable," with a Richardson number greater than 0.2?  (Hint: Histograms might be helpful here -- reach out if you need coding help with conditional histograms.) 

 
 ```tip
Remember, our sensors measure the kinematic flux of specific humidity times velocity (units of kg_water/kg_air m/s).  To calculate an actual equivalent water loss from teh snowpack, we need to convert to units of actual flux (kg_water/(m^2*s)). To convert, we multiply by the density of air, which we can calculate from the ideal gas law, as shown in Lab 7-1.   
```

### Problem 2: Mass vs Energy Fluxes in Sublimation
Consider again, the major wind event of 22 December 2021 that moved a fair bit of snow around.  Over the 24-hour period of measured blowing snow at 1 m (as documented by the FlowCapt sensor), calculate (a) the total mass (in grams/m^2) of snow that horizontally moved past the sensor, (b) the total mass (in grams) or water vapor that was transported vertically away from the snow over this time interval, (c) the total energy (in Joules, using the latent heat of sublimation) that went into converting snow to the amount of water vapor calculated in b, and (d) the total energy change per m^2 area, in the snowpack, calculated with the specific heat of ice, the density of ice * the depth over which a change was observed, and the observed temperature change (as measured from the thermistors in the snowpack at this time).

