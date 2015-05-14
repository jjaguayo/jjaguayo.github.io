---
title: Brainstorm
img: dti.png
pitch: >
  Compiling code by configuring connections
---
Brainstorm is a programmable million neuron low-power analog chip 
running networks designed with the Neural Engineering Framework (NEF).

With a power budget of 12 watts, the brain perceives, decides and acts. 
KAIST&rsquo;s battery-powered [HUBO 2](http://ohzlab.kaist.ac.kr/r_op){:target="_blank"} 
robot uses over a quarter of its energy 
just to control walking even in predictable environments. 
[BrainGate](http://nurmikko.engin.brown.edu/?q=node/1){:target="_blank"}&rsquo;s 
implantable brain machine interface (BMI) uses half of its energy to 
wirelessly transmit recorded neural signals because it cannot decode the 
intended movement. How can engineers build processors as energy-efficient 
as the brain? Our approach is to mimic its graded dentritic potentials 
using analog circuits and its all-or-none axonal spikes using digital 
circuits. To compute with our energy-efficient silicon neurons, we use 
[NEF](http://nengo.ca/node/5){:target="_blank"}.

NEF enables us to compile perceptual, cognitive and motor algorithms onto 
networks of spiking neurons.

Developed by Eliasmith and Anderson, NEF defines three principles. First, a 
population of neurons collectively represents a time-varying vector through 
nonlinear encoding and linear decoding. Second, alternative linear decodings 
that transform the vector (linearly or nonlinearly) are used to compute 
weighted connections from one neural population to the next. Third, recurrent 
connections—from a neural population back to itself—realize a transformation 
that governs the vector&rsquo;s dynamics.

Our ultimate goal is to build an autonomous robot that perceives, decides 
and acts using large-scale networks of silicon neurons. 

Our robot will perceive the world through a silicon retina, decide what to do 
using a silicon cortex, and act on the world with a mechanical arm. Currently, 
we are using NEF to configure silicon neurons to decode intended movements 
energy-efficiently for a next-generation implantable BMI and to control a 
robotic arm energy effiently for a next-generation humanoid robot. We are also 
architecting an NEF chip capable of implementing networks large enough to realize 
a fully cognitive system. 
