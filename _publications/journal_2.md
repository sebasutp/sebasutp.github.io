---
title: "Real time trajectory prediction using deep conditional generative models"
collection: publications
category: manuscripts
permalink: /publication/journal_2
excerpt: 'A Variational-Autoencoder for trajectory forecasting'
date: 2020-01-14
venue: 'IEEE Robotics and Automation Letters'
paperurl: '/files/paper2.pdf'
citation: 'S. Gomez-Gonzalez, S. Prokudin, B. Schölkopf and J. Peters, "Real Time Trajectory Prediction Using Deep Conditional Generative Models," in IEEE Robotics and Automation Letters, vol. 5, no. 2, pp. 970-976, April 2020, doi: 10.1109/LRA.2020.2966390'
---

# Abstract

Data driven methods for time series forecasting that quantify uncertainty open new important possibilities for robot tasks with hard real time constraints, allowing
the robot system to make decisions that trade off between
reaction time and accuracy in the predictions. Despite the
recent advances in deep learning, it is still challenging to
make long term accurate predictions with the low latency
required by real time robotic systems. In this paper, we
propose a deep conditional generative model for trajectory
prediction that is learned from a data set of collected
trajectories. Our method uses encoder and decoder deep
networks that map complete or partial trajectories to a
Gaussian distributed latent space and back, allowing for
fast inference of the future values of a trajectory given
previous observations. The encoder and decoder networks
are trained using stochastic gradient variational Bayes. In
the experiments, we show that our model provides more
accurate long term predictions with a lower latency than
popular models for trajectory forecasting like recurrent
neural networks or physical models based on differential
equations. Finally, we test our proposed approach in a robot
table tennis scenario to evaluate the performance of the
proposed method in a robotic task with hard real time
constraints.