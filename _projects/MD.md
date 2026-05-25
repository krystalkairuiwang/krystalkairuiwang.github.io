---
title: "Molecular Dynamics Simulation Analysis"
header_image: "/assets/images/kagome.jpg"
description: "Python script to analyze lattice composition in Molecular Dynamics simulations"
layout: "project"  # We'll create a project layout or use default
technologies:
  - Python
  - lammps
---

2025

At the <a href="https://aryalab.pratt.duke.edu/">Arya Lab</a>, our project focused on optimizing the self-assembly of DNA
nanotechnology through Machine Learning. One method of demonstrating the change in self-assembly performance was through analyzing
the presence of lattice structures in the molecular dynamics (MD) simulations. 

I was tasked with writing a python script that can automatize the recognition and extraction of unit cells of a lattice. Expanding on previous code that detected geometric patterns within the lattice, I devised an algorithm that filtered out irregular formations and identified the unit cells that, when repeated, can form the perfect lattice. 

This was an interative process of devising definitions of "lattice" and "unit cells" that the program can follow,
then adapting the code to more complex cases, such as when multiple lattices are present in one simulation. This 
project required me to collaborate with other people's code, learn and format the outputs in the style of MD simulation lammps files,
and debug both the algorithm and the python code.

(Unpublished work)

## Workflow Demonstration

<img src="/assets/images/workflow1.png" alt="workflow image 1" style="width:800px;">
<img src="/assets/images/workflow2.png" alt="workflow image 2" style="width:800px;">
<img src="/assets/images/workflow3.png" alt="workflow image 3" style="width:800px;">