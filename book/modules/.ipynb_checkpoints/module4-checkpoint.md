# 4) Mass Balance:  Blowing snow, wind, and how snow smoothes landscapes

# Background

[![Watch a video of Ethan Gutmann explaining how scanning lidars can detect both snow depth and blowing snow](https://img.youtube.com/vi/-9Mt2mrmAy8/0.jpg)](https://www.youtube.com/watch?v=-9Mt2mrmAy8)

In the video above, Ethan explains how the scanning lidars work, while Jessica looks at the lidar equipment.  In the [video linked here](https://www.youtube.com/watch?v=rlwSuNWQHSo) Ethan takes the lidar away from Jessica and explains how it works more succinctly.  You can vote which one you think is more useful for inclusion in the final class website.

**To learn more about the basic atmospheric dynamics of wind**
* [COMET](https://www.meted.ucar.edu/education_training/) offers online classes on many topics in meteorology. Note that you need to register, but their classes are free. Here I've linked to some lessons relevant to mountain snow, but there are many more.
* COMET MetEd module on [basic dynamic meteorology and atmospheric relationships between temperature, pressure, and wind](https://www.meted.ucar.edu/education_training/lesson/889)

**To learn more about mountain scale winds and how they impact snow accumulation at a watershed scale**
* article by former UW student Dylan Reynolds about [Using lidar snow maps to evaluate atmospheric wind fields](https://doi.org/10.1029/2020WR028536)
* the COMET education program has a short lesson on valley wind circulations [here](https://www.meted.ucar.edu/education_training/lesson/55) 
* COMET also has two lessons by David Whiteman on the planetary boundary layer (including mountain wind systems) over complex terrain, available [here](https://www.meted.ucar.edu/norlat/pbl_complexterrain/part1/) and [here](https://www.meted.ucar.edu/norlat/pbl_complexterrain/part2/).

**To learn more about blowing snow and snow on the ground, check out**
* article by Charles Parr, Matthew Sturm and Chris Larsen about [Arctic Snowdrift Patterns](https://doi.org/10.1029/2020WR027823).  
* article by Simon Filhol and Matthew Sturm about [Snow Bedforms](https://doi.org/10.1002/2015JF003529)
* Watch Matthew Sturm's lecture on [wind and snow](https://www.youtube.com/watch?v=rBlDG9Tp8rM&list=PLPG5Ed5L1SY4RpFe-55WAlFZ58-TwwrWw&index=6).  (Note that this is labeled as Lecture 6 and starts at minute 13:48 on the linked video.) 

```note
## Lab 4: Wind Speed and Particle Flux

Download the lab and data files to your computer. Then, upload them to your JupyterHub [following the instructions here](/resources/b-learning-jupyter.html#working-with-files-on-our-jupyterhub).

* [Data: sos_wind_snowflux.nc](data/snow_wind_snowflux.nc) 
* [Data: lidar_l2_particles.nc](data/lidar_l2_particles.nc) 
* [Lab 4-1-long: Downloading and Plotting wind speed](lab4/lab4-1-long.ipynb)
* [Lab 4-1-short: Just Plotting wind speed](lab4/lab4-1-short.ipynb)
* [Lab 4-2: Comparing wind speed with snow particle fluxes](lab4/lab4-2.ipynb)
* [To hear Ethan explain the FlowCapt sensors used in the lab, click here](https://youtu.be/07um8VtGj-g ) 


```


## Homework 4

### Problem 1, based on combining material in Labs 2 & 3 and Modules 2 & 3

In Lab 2 and Module 2, we saw that in late December, one of the four snow pillows had a sudden increase in snow water equivalent while the other three had a decrease.  In Lab 3, we saw a similar pattern in the snow depth measurements near of the snow pillows.  Look at the snow depths, the snow densities, wind speeds, and snow particle fluxes during this period.  Create plots to help explain what is happening here. Referencing your plots, explain what happened in Kettle Ponds during this period.  You may also want to check out the [weekly weather blog.](https://depts.washington.edu/mtnhydr/Pages/SOSdata.html) 

### Problem 2: Testing wind thresholds and particle counts

There is a threshold wind speed that must be exceeded for snow transport.  [Li and Pomeroy 1997](https://doi.org/10.1175/1520-0450(1997)036<0205:EOTWSF>2.0.CO;2) state that 10-m wind speeds must exceed about 7.7 m/s for dry snow transport and about 9.9 m/s for wet snow transport.  Use the 10-m wind speed measurements and particle counters to test if these thresholds match the observations at Kettle Ponds.  If you have time, further discuss the questions at the end of Lab 4-2.


### Problem 3: Project

Please give a brief update of where you are with your project.  Let me know if you have any questions or concerns at this point.
