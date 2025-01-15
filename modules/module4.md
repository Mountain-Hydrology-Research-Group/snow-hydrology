# 4) Temperatures: snowpack and atmospheric stability 

## Temperatures in the snowpack - expanding the snowpack energy balance equation

From Module 3, we know the snow energy balance can be written

$$\frac{d}{dt} (U \Delta z) = LW_{in} + LW_{out} + SW_{in} + SW_{out} - H_L - H_s + E_{melt} + G$$

where $U$ is the internal energy of the snow pack and ∆z is the snowpack depth. See Module 3 for a description of the other terms.  The internal energy ($U$) of the snowpack is a function of the temperature, density, and specific heat capacity of the snowpack. Mass has internal energy, so generally one would consider a _volume_ of snow to have internal energy, but in our case, we are interested in energy fluxes, and so we use the depth of the snowpack. This is best explained by doing some dimensional analysis. The internal energy of snow, per kilogram, is approximately

$$ U =c_p^{ice} \langle \rho_s T_s \rangle $$

where the angle brackets indicate depth-averaging of the snow temperature and snow density. This equation has units

$$U = [kg m^{-3}] [J K^{-1} kg^{-1}] [K] = J m^{-3} $$

We want the units to be J m^-2, so we simply multiply by the depth of the snowpack (∆z), and take the derivative with respect to time

$$\frac{d}{dt} (U \Delta z) = \frac{d}{dt} \big( c_p^{ice} \Delta z \langle \rho_s  T_s \rangle \big)$$

which is in units of W m^-2 as desired (remember, 1 Watt = 1 Joule / second).
Generally, we assume that snow density and depth are changing slowly, at least more slowly than the snowpack temperature, and thus we could pull those terms out of the time derivative to get

$$ c_p^{ice} \Delta z \langle \rho_s \rangle \frac{d}{dt} \langle T_s \rangle = LW_{in} + LW_{out} + SW_{in} + SW_{out} - H_L - H_s + E_{melt} + G$$

Note that the equation above implies that to accurately measure the internal energy of snow, we need measurements of temperature and density throughout the depth of the snow. 
Also, if it turns out that snow density and snow depth do NOT change slowly, we need to include those terms within the time derivative, which complicates things.


```note
## Lab 4: Snowpack temperatures and snowpack internal energy

* [Lab 4-1](lab4/lab4-1.ipynb)
* [Lab 4-2](lab4/lab4-2.ipynb)
* [SoS dataset](data/sos_full_dataset_30min.nc)
```

## Homework 4

### Problem 1: Snowpack temperature profiles
In Lab4-2, we plotted vertical profiles of snowpack temperature on multiple, sequential days.
Replicate these plots for all days from the first half of April (April 1--15).
Find 4-5 days during this period where some significant behavior in the snowpack temperatures changes. 
Isolate the plots to only these 4-5 days. What is going on here? Why are the snowpack temperatures acting the way they are?

### Problem 2: Snowpack internal energy
