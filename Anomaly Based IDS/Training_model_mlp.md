# Traning Model using MLP

This model, when built, will be used by testing dataset to classify which of the instances, leading to  being classified as normal or anomaly.

Kappa statistics above 0.81 is said to be a perfect agreement.

### Steps
(1) Under 'Classify' tab, choose 'Classifier' as 'MultiLayerPerceptron' under 'functions'.<br />
(2) Under 'MultiLayerPerceptron', opt 'True' under GUI if you want to witness what is actually happening with our model.<br />
(3) Choose 'hiddenLayers' as per requirement. I have taken it as 2 as adding hidden layers makes the model more complex.<br />
(4) 'learning rate' and 'momentum' is chosen after a lot of hit and trial.<br />
(5) Now, check 'use trianing set' under 'Test options'.<br />
(6) Select 'Start'.

