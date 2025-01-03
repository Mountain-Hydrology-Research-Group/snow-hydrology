# 3) Surface Energy Balance – Radiation + Albedo, Dust on Snow

# Background
![Photo of April 2023 dust event at Kettle Ponds](data/Dust_on_SOS.png)

The balance of energy over a snow surface is a phenomenon studied by both biologists, hydrologists, boundary layer meteorologists, and snow scientists. Many fields use the surface energy balance (SEB) to estimate evaporation and transpiration of water from the earth's surface. Meteorologists study the SEB's radiative effects on the atmosphere.

The surface energy balance equation balances incoming and outgoing sources of energy at the surface, measured in terms of energy flux (energy per units area, i.e. W/m^2, Watts per meters squared). 
We as snow scientists are generally interested in the SEB to understand the energy available for snow melt and snow sublimation. 
Therefore, we augment the more standard version of the surface energy balance equation to include terms involving phase changes and energy storage changes (temperature change) within the snowpack. 
The snowpack energy balance equation can be written

$$c_p^{SS} \frac{\partial T_{ss}}{\partial t} = LW_{in} + LW_{out} + SW_{in} + SW_{out} - \lambda \frac{\partial T_s}{\partial z} - H_L - H_s + E_{melt}$$

where 

$c_p^{SS} \frac{\partial T_{ss}}{\partial t}$
represents the change in the snow surface temperature ($c_p^{SS}$ is the specific heat capacity of the snowpack surface and $T_{ss}$ is the snowpack surface temperature),

$LW_{in} + LW_{out}$ is the incoming and outgoing longwave radiation (AKA infrared radiation),

$SW_{in} + SW_{out}$ is the incoming and outoing shortwave radiation (ultraviolet, visible, and near-infrared radiation; all sourced from the sun),

$\lambda \frac{\partial T_s}{\partial z} $ is the change in the "cold content" of the snowpack, i.e. the change in the vertically averaged temperature of the snowpack,

$H_L$  is the vertical flux of *latent heat* away from the snowpack surface, i.e. the flux of water vapor away from the snowpack, either through sublimation or perhaps evaporation from melted water at the snowpack surface, 

$H_s$ is the vertical flux of *sensible heat* away from the snowpack surface, i.e. the flux of temperature away from the snowpack, i.e. the heating or cooling of the lower atmosphere by the snowpack,

and, lastly,

$E_{melt}$ is the energy that goes to the latent heat involved in the melting of snow.

Snow scientists are generally most interested in snow melt ($E_{melt}$) and snow sublimation ($H_L$) and the majority of the energy available for snow melt or sublimation comes from the net radiation, the balance of incoming shortwave, reflected shortwave, incoming longwave, and emitted longwave radiation. Incoming shortwave radiation ($SW_{in}$) comes from the sun and is a function of time of year, time of day, cloud cover, atmospheric aerosols, and topographic position. We can predict/model potential SW radiation well, although in complex/mountainous terrain, topography matters a lot.

Incoming shortwave radiation at the snowpack's (earth's) surface is a result of the sun's output radiation and the interaction of with that incoming radiation on earth with the atmosphere. 
Gasses in the atmopshere, mostly water vapor, absorb shortwave radiation, such that $SW_{in}$ at the earth's surface is always lower than at the outermost edge of the atmosphere. 
Therefore, clouds can reduce the amount of incoming shortwave radiation at the earth's surface.
Snow is highly reflective, returning 60-90% of the incoming SW radiation to the atmosphere, i.e. snow has a high [*albedo* ($\alpha$)](https://mynasadata.larc.nasa.gov/mini-lessonactivity/what-albedo). 
Albedo, $\alpha$, varies between zero and 1; a highly reflective surface reflects most of the incoming solar radiation ($\alpha$ approaches 1) and non-reflective surfaces absorb most of the incoming solar radiation ($\alpha$ approaches 1). Snow albedo varies between 0.6 and 0.9. although dirt, dust, and rocks on snow or glacier surfaces can decrease the surface-averaged albedo significantly. 

Longwave radiation is output by all mass in the universe, and the output LW radiation is proportional to the surface temperature of the mass, according to the [Stefan–Boltzmann Law](https://en.wikipedia.org/wiki/Stefan–Boltzmann_law), which states that energy radiated per unit surface area per unit time (i.e. energy flux at the surface) is equal to the fourth power of the black body's (surface's) temperature, and therefore the outgoing longwave radiation (i.e. the energy emitted by the earth into the atmosphere) is defined

$LW_{out} = \epsilon \sigma T^4$$,

where $\epsilon$ is the Stefan–Boltzmann constant ($\sigma \approx 5.67 × 10^{−8} \space W⋅m^{-2}⋅K^{-4}$)
and $\epsilon$ is the emisivity of the surface emitting the radiation ($\epsilon$ varies between zero and one). The snowpack surface [emissivity](https://www.jpl.nasa.gov/images/pia18833-nasa-spacecraft-maps-earths-global-emissivity) is near 1, meaning that the snowpack surface (i.e. water molecules) absorb most of the incoming LW radiation, and reflect very little. $epsilon$ for the snowpack depends on snowpack properties, but a commonly assumed value is $\epsilon = 0.985$.

Note that the Stefan-Boltzmann law implies that when gases in the atmosphere (i.e. clouds) absorb incopming shortwave/solar radiation and warm up, they increase their output of longwave radiation. 
This means that the presense of clouds, while decreasing incoming solar radiation at the snow surface, increase incoming longwave radiation at the snow surface.

The reflective properties of the snow surface, for both longwave and shortwave radiation, mean that the longwave terms and shortwave terms in the energy balance equation we started with can be rewritten,

$$LW_{in} + LW_{out} = LW_{in} - \epsilon \sigma T_{ss}^4$$

and

$$SW_{in} + SW_{out} = (1 - \alpha) SW_{in}$$

and therefore

$$c_p^{SS} \frac{\partial T_{ss}}{\partial t} = LW_{in} - \epsilon \sigma T_{ss}^4 + (1 - \alpha) SW_{in} - \lambda \frac{\partial T_s}{\partial z} - H_L - H_s + E_{melt}$$

In cooperation with the Sublimation of Snow campaign, NOAA is conducting the [Study of Precipitation, the Lower Atmosphere and Surface for Hydrometeorology, SPLASH, campaign](https://psl.noaa.gov/splash/). From the prior link, if you click on _data_ and on _KettlePonds_, you can see photos of the radiometer and streams of data. 

For today's lab, we will bring in one of the [Superheros of SPLASH](https://storymaps.arcgis.com/stories/093640ac6bdc479394d7fd9c7068fd27) to help us with our investigation.

For even more detailed information about clouds, aerosols, and radiation, DOE is conducting the [Surface Atmosphere Integrated Field Laboratory, SAIL, campaign](https://sail.lbl.gov/), with a list of sensors [here](https://sail.lbl.gov/what-we-measure/).

```note
## Lab 3: Plotting radiation data around the snow.

Download the lab and data files to your computer. Then, upload them to your JupyterHub [following the instructions here](/resources/b-learning-jupyter.html#working-with-files-on-our-jupyterhub).

* [Lab 3-1: Plotting Radiation Data at Kettle Ponds and Potential Radiation](lab3/lab3-1.ipynb)
* [SPLASH radsys_attribute data, used in lab3-1](data/radsys_attributes.txt)

```

## Homework 3
Radiometers are used to measure the radiation components of the surface energy balance.
One type of instrument, a "net radiometer" or "four-stream radiometer", measures incoming and outgoing longwave and shortwave radiation using four sensors built into a single instrument. An image of a type of radiometer used by the Sublimation of Snow Campaign, the [Hukseflux NR01](https://www.hukseflux.com/products/pyranometers-solar-radiation-sensors/net-radiometers/nr01-net-radiometer), is shown below.

[<img src="data/huskeflux_nr01.png" width="400"/>](data/huskeflux_nr01.png)

### Problem 1: Comparing solar radiation sensors
A common problem in snow energy balance studies is that snow accumulates on the upward pointing radiometers (see image below, compliments of [Lapo et al., 2015](https://doi.org/10.1002/2015WR017590)).

[<img src="data/radiometer_snow_covered_lapoetal_2015.jpg" width="800"/>](data/radiometer_snow_covered_lapoetal_2015.jpg)

Use the precipitation dataset from Lab 2 to examine both incoming and outgoing radiation measurements during and after times with precipitation.
Find a time in the dataset when you think snow covered the radiometer and explain why this occurred.

You may find that skimming [Lapo et al., 2015](https://doi.org/10.1002/2015WR017590) is useful (Karl Lapo is a graduated, former UW PhD student).

### Problem 2: Clouds
Identify two periods of variable cloud cover in the dataset, one during nighttime and one during daytime.
You can use shortwave radiation measurements to identify what is day/night.
Explain why and how you can use both shortwave and longwave measurements to identify variations in cloud cover.
Explain what both shortwave and longwave radiation tell you about the cloud cover.

### Problem 3: Dust on snow and albedo
The reflectivity of snow, AKA albedo ($\alpha$), is defined

$$\alpha = \frac{SW_{out}}{SW_{in}}$$.

It is understood intuitively to most people in cold climates that snow is brightest right after new snowfall, and darkens as it ages.
This is a result both of the rounding and growing of snow grains as well as the "dirtying" of snow through the deposition of atmospheric deposition particulates.
In April, 2024, a substantial amount of dust was deposited on our site at Kettle Ponds (see the photo at the top of this page).
Calculate and plot albedo during April the first half of April and identify the date on which you think dust was deposited. 

Find a day or two with precipitation from earlier in the season (say, January) and plot albedo during and after the snowfall event.

How does the effect of snow "aging" on albedo differ from the effect of dust deposition on albedo?