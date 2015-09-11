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
<img src="/media/we_0.jpg" alt="Drop splash"  width="200" style="float:left">
<img src="/media/we_760.jpg" alt="Drop splash"  width="200" style="float:left">
<img src="/media/we_1380.jpg" alt="Drop splash"  width="200" style="float:left"> </br>

<video width="320" height="240" controls autoplay>
  <source src="/media/movie_ar0-5.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video> 
<video width="320" height="240" controls autoplay>
  <source src="/media/movie_spin_200.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video> 
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
