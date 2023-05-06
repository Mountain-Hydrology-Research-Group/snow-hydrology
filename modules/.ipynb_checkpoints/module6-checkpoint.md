# 6) Temperatures above, below, and within the snow

Data visualization (Note, the files below were developed by Steven Pestana for working with air temperature data but may be helpful with visualizing our snow data):
- [Interactive Plots](lab5/interactive-plots.ipynb) with [iButtons_2008-2010.mat](data/iButtons_2008-2010.mat)
- [Warming Stripes Figure](lab5/warming-stripes.ipynb)

# Background
![Here are February temperatures at Kettle Ponds](data/SoSFebtemps.png)

### Temperatures in the Snow
* To see Danny explain the snow temperature deployment, click [here](https://www.youtube.com/watch?v=OGa2GtRcdIw)

### Air temperatures in the mountains
* For an overview of mountain temperatures and lapse rates, check out Jessica's seminar on [How cold is it in the mountains](https://youtu.be/saUe3uIegRs) 


```note
## Lab 6: Plotting temperatures in and around the snow.

Download the lab and data files to your computer. Then, upload them to your JupyterHub [following the instructions here](/resources/b-learning-jupyter.html#working-with-files-on-our-jupyterhub).

* [Lab 6-1: Temperatures in and below the snow and the heat equation](lab6/lab6-1.ipynb)
* [Lab 6-2: Snow surface temperatures derived from radiation](lab6/lab6-2.ipynb)
* [Lab 6-3: Air temperature and atmospheric stability](lab6/lab6-3.ipynb)
* [BONUS Lab 6-4: Sounding data from SAIL at Gothic, CO](lab6/lab6-4.ipynb)

```

## Homework 6

### Problem 1: Measuring snow temperatures and deciding how to trust the measurements  


 
 ```tip
This is a tip.
```

### Problem 2: Working with the heat equation
We have talked in class about snow being insulating and about the surface skin temperature of the snow changing rapidly in time.  But how is energy at the surface translated into the lower layers?  We can estimate the thermal conductivity of our snowpack using the one-dimensional heat equation. 

The one-dimensional heat equation is given by:

$$
\frac{\partial T}{\partial t} = \alpha \frac{\partial^2 T}{\partial z^2}
$$

where $T(z,t)$ is the temperature at position $z$ and time $t$, and $\alpha$ is the thermal diffusivity of the material.

Using the material provided in Lab 6-1, pick a period of about 5-7 days wherein (a) you trust the temperature measurements and (b) that have a clear diurnal cycle in the surface temperature.  Assign that rapidly varying surface temperature as one boundary condition and provide the lowest temperature (you can presume it's constant0 as the other boundary condition.  Then, numerically integrate the heat equation to determine the time-varying temperatures at the snow layers in between.  Comparing your simulation with the observations, what is your best guess of the thermal conductivity of the snowpack?  Hint, you may want to rerun your simulation, iterating over multiple values of thermal conductivity.  



### Problem 3:  Calculating atmospheric stability


