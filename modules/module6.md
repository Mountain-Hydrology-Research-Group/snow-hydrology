# 6) Blowing snow transport and sublimation

I highly recommend watching Dr. Matthew Sturm's Lecture on blowing snow, snow dunes, and other snow landforms. 

[Lecture on blowing snow](https://youtu.be/rBlDG9Tp8rM?si=dqCCF-sW0NXQYG5i&t=3658)

For our lab, we will try to do something not covered closely in the video - estimating the sublimation rate of blowing snow.

We will estimate the rate with two simple methods, which provide opportunity for future improvement.

In the atmospheric boundary layer, the conservation of water equation often simplifies to 

$$S = \frac{\partial \overline{w'q'}}{\partial z}$$

where $S$ is a source term (grams of water vapor per m^3 of air), representing addition of water vapor to the atmosphere by blowing snow sublimation, and the derivative term represents the change in the vertical turbulent flux of water vapor with height above the snow surface.

When the derivative term is positive, a higher EC (e.g. 10m) may measure larger $\overline{w'q'}$ than a lower EC (e.g. 3m). This was observed at Kettle Ponds during a blowing snow event on 21--22 December 2022 (Lundquist et al., 2024, DOI 10.1175/BAMS-D-23-0191.1).

Using a finite different approximation to the derivative above, one could try a *very rough* estimation of the blowing snow sublimation rate.

$$
S = \frac{\partial \overline{w'q'}}{\partial z} 
= \frac{\Delta \overline{w'q'}}{\Delta z} 
= \frac{
    \overline{w'q'}_{z=10m} - \overline{w'q'}_{z=1m}
}{\
     10 - 1 \text{m}
}

 \quad \Bigg[ \frac{\text{g/m}^2\text{/2}}{\text{m}} \Bigg] \Rightarrow \Bigg[ 
    \frac{\text{g}}{\text{m}^3} 
\Bigg]
$$

