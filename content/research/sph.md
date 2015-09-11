+++
Categories = ["Research", "CFD"]
Description = ""
Tags = ["Development", "golang"]
date = "2015-08-08T12:46:55+05:30"
menu = "code"
title = "SNU: The SPH solver"
type = "code"
+++

SNU is an Incompressible Smoothed Particle Hydrodynamics (ISPH) solver with the following capabilities

* Solves a new volume conserving pressure equation
* Uses an improved free surface model 
* Ghost particles for boundaries
* High density ratio multiphase flows
* Fluid Structure interaction with rigid bodies
* 3D code, parallelized using OpenMP (a GPU version is also available)

## Some simulation results
Simulation of a drop impacting a thin liquid film. Four million particles were used in this simulation</br> 
<div>
<img src="/media/mo_0.png" alt="Drop splash"  width="300" style="float:left"><img src="/media/mo_3.png" alt="Drop splash"  width="300" style="float:left">
</div>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
Water entry of a sphere at very low Froude number. 
</br>
<img src="/media/we_0.jpg" alt="Drop splash"  width="200" style="float:left">
<img src="/media/we_760.jpg" alt="Drop splash"  width="200" style="float:left">
<img src="/media/we_1380.jpg" alt="Drop splash"  width="200" style="float:left"> </br>
</br>
</br>
</br>
</br>
</br>
Wash away of a solid during dam break </br> 
<video width="612" controls autoplay>
  <source src="/media/dam.webm">
  Your browser does not support the video tag.
</video> 
</br>
</br>
Water Entry of a streamlined solid and a spinning solid</br> 
<video width="320" height="240" controls autoplay>
  <source src="/media/movie_ar0-5.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video> 
<video width="320" height="240" controls autoplay>
  <source src="/media/movie_spin_200.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video> 
</br>
</br>
</br>
Surface tension simulations</br> 
<video width="320" height="240" controls autoplay>
     <source src="/media/movie_cube.mp4" type="video/mp4">
       Your browser does not support the video tag.
</video> 
<video width="320" height="240" controls autoplay>
     <source src="/media/movie_coal_p_int.mp4" type="video/mp4">
       Your browser does not support the video tag.
</video> 
<video width="320" height="240" controls autoplay>
     <source src="/media/movie_st_2d.mp4" type="video/mp4">
       Your browser does not support the video tag.
</video> 
## Validations
Lid Driven cavity simulations for Reynolds number 400 (top) and 1000 (bottom)
<div>
<img src="/media/Fig_4a.jpg" alt="Lid Driven Cavity"  width="600" style="float:left"><img src="/media/Fig_4b.jpg" alt="Lid Driven Cavity"  width="600" style="float:left">
</div>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
Dambreak simulation (Re ~ 40000). The improved free surface model is used in this simulation. </br>
The colors show the velocity magnitude. 
<video width="612" controls autoplay>
  <source src="/media/dambreak2d.webm">
  Your browser does not support the video tag.
</video> 
</br>

