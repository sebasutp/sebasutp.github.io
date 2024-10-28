---
title: "Robot Table Tennis"
excerpt: "We used machine learning in all the components: The actual robot policy, the vision system and the system that predicts the trajectory of the ball.<br/><img src='/images/fh_teach.png' width=500>"
collection: portfolio
---

We used machine learning in all the components: 
* The actual robot policy consisted of a probability distribution of robot trajectories (Learned from the human teacher - See in the video). We used a representation called probabilistic movement primitives.
* The vision system used simple logistic regression to find the color of the ball in the images at 200 frames per second. We also used outlier detection and correction to improve the quality of the system.
* Finally, we also used a supervised learning model to predict the future trajectory of the ball from the previous ball observations.

<iframe width='560' height='315' src='https://www.youtube.com/embed/KLK4IwpgEB4' title='Robot Table-Tennis Video' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;   
 web-share' allowfullscreen></iframe>