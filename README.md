# Brown-Datathon
Analysis of the Dassault Systems sponsored project to use ML to ease physics based simulations at The Brown Datathon Feb 2020. 

Problem Statement:

We used recently developed physical simulation technology [1] to compute meltpool shapes and temperature field of an Selective Laser Melting (SLM) AM process for Ti64 alloy. Given machine parameters such as laser power, laser speed, laser scan direction as well as layer boundary parameters, the finite element simulations predict time dependent meltpool size and temperature field when laser travels through the top of a part surface.

For each case, the task is as follows:

Given laser power, laser speed, x/y/z coordinate of a specific point, predict the temperature at that point; also, given laser power and laser speed, predict the meltpool L/width/depth;

Given laser power, laser speed, edge angle, edge distance, laser direction, x/y/z coordinate of a specific point, predict the temperature at that point; also, given laser power, laser speed, edge angle, edge distance, and laser direction, predict the meltpool L/width/depth.

We'll look at a simple exploration and visualization of these data in the next section.

Due to data provacy issues and NDA, the data and results of EDA have been removed. But,the code is available for viewing.


The Presentation is available for viewing here (https://docs.google.com/presentation/d/18h7ktf0n26R5-Pz4Z-gnBjpOT0Kt0xXevqwhKzo7TFo/edit?usp=sharing)
