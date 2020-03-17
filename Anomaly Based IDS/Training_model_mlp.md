---
title: "Traning Model using MLP"
author: "Prabhat Amola"
date: "17/03/2020"
output: html_document
---

This model, when built, will be used by testing dataset to classify which of the instances, leading to  being classified as normal or anomaly.

Kappa statistics above 0.81 is said to be a perfect agreement.

#Steps
(1) Under 'Classify' tab, choose 'Classifier' as 'MultiLayerPerceptron' under 'functions'.
(2) Under 'MultiLayerPerceptron', opt 'True' under GUI if you want to witness what is actually happening with our model.
(3) Choose 'hiddenLayers' as per requirement. I have taken it as 2 as adding hidden layers makes the model more complex.
(4) 'learning rate' and 'momentum' is chosen after a lot of hit and trial.
(5) Now, check 'use trianing set' under 'Test options'.
(6) Select 'Start'.

