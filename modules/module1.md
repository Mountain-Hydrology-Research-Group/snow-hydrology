# 1) What is snow? Phases and properties of matter

Each week, the labs are designed to give you specific coding examples to help you with that week's homework.
Please look through the background and lab material before beginning the homework.  Note that the first week's lab has a lot of examples to help people learning python.  This will get easier as we go.

# Background

"So mom, liquid water is just water, and solid water is ice, so what is snow?  I can walk on it, so it's solid, but it's not the same as ice."

Very few substances exist in all three phases in nature.  We experience water vapor, water, and ice so frequently that we forget how unique they are.
(https://en.wikipedia.org/wiki/Phase_diagram#/media/File:Phase_diagram_of_water.svg) 

To understand how water changes phase within the atmosphere and within a snowpack, we need to understand basic chemistry. 
[Growing snowflackes with Ken Libbrecht](https://www.youtube.com/watch?v=ao2Jfm35XeE) 
We may not have a lab of this quality, but you can print and build your own hexogonal snow crystal out of [paper](data/CutOutIceCrystalPrism_Aug25.jpg).  

---

```note
## Lab 1: Plotting Data and Calculating the Energy of Phase Changes in Python

Download the lab and data files to your computer. Then, upload them to your JupyterHub [following the instructions here](../resources/b-learning-jupyter.html#jupyterhub).

* Download this data file for the lab activities: [Skykomish peak flows](data/Skykomish_peak_flow_12134500_skykomish_river_near_gold_bar.xlsx)
* [Lab 1-1: Plotting Data in Python](lab1/lab1-1.ipynb)
* For more practice in plotting, try this graphical data analysis lab: - [Graphical Data Analysis](lab1/graphical-data-analysis.ipynb) with this [sample data set](data/my_data.csv)
* [Lab 1-2: Phase Changes](lab1/lab1-2.ipynb)


Some extra helpful activities:
* [Numpy Tutorial](lab1/numpy-tutorial.ipynb)
* [Some more python tips](lab1/some-python-tips.ipynb)

```

---

## Homework 1

In this homework assignment we will work start with programming and data visualization to better qualitatively understand the types of datasets that we'll be using the rest of the quarter.  Please download the notebooks at the top of this page and use them as reference for your coding.  **Be sure to save your work for later reference**


### Water and States of Matter

For this week's homework, we will pretend we are in very controlled laboratory conditions.  If you dislike python, these questions can all be answered with pencil, paper, and a calculator, but you may want to use this exercise as a chance to practice your programming skills.

 A. Imagine you have a 1 cubic centimeter block of ice at -10 degrees C and 1 atm of pressure.  Calculate the amount of energy required to **melt** all of the ice.  (Note that you will have to warm it to 0 degrees C before you begin melting it.)

 B. Now, consider that same block of ice at -10 degrees C and 1 atm of pressure.  Calculate the amount of energy required to **sublimate** all of the ice.  (Note that you do not need to warm the ice to sublimate it.)
 
 C. Repeat the calculations above, but imagine you are high in the mountains at 0.5 atm of pressure.  What changes?

---
