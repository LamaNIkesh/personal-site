---
title: "Gaussian Process Doge Coin Price Prediction"
date: 2021-10-02T16:06:17+01:00
draft: false
tags: 
- Gaussian Process
- Bayesian
- Doge coin
- Gaussian Distribution
- Multivariate Gaussian 
- Kernel
- Covariance Matrix
---

> Full jupyter notebook can be viewed and downloaded from my *[ github](https://github.com/LamaNIkesh/GaussianProcess/blob/main/dogecoin_GP.ipynb)* .Feel free to ask questions and raise issues. 

### Why?

Gaussian process has eluded me for many years. I tried learning it many times, felt like I understood it, but not quite enough to implement for a real problem. I set aside a couple days and started learning and understanding so that I have a good intuition of the algorithm. Slowly building the intuition really helped me understand it better. I first started with [GradientPub](https://thegradient.pub/gaussian-process-not-quite-for-dummies/) and also followed [lecture](https://www.youtube.com/watch?v=92-98SYOdlY) by Dr Richard Turner and [lecture series](https://www.youtube.com/watch?v=4vGiHC35j9s) by Prof Nando De Freitas. The most recommended book for Gaussian Process is [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/gpml/chapters/RW.pdf) by Carl Edward Rasmussen and Christopher K. I. Williams. I tried to start with the book but my limited maths and statistics knowledge was immediately apparent so I left the book for later once I grasped the intuition behind the concept. 

To test my understanding, I decided to use GPs for a simple prediction problem for currently popular DogeCoin. 

### What is the project? 

Dogecoin price prediction based on the past 6 months data using non-parametric gaussian process (GP). GPy library is used for the implementation and optimisation.

### Challenges
Choosing the right kernel is the main crux of using GPs. I tried a combination of linear, exponential and periodic kernels to get the best result[Lot more to improve!!]. Due to the stochastic nature of the time series, I though may be brownian kernel would be better but didn't work out well. Predicting the missing values in the data seems to work better than predicting future after a certain time point. 

### Result

{{< figure src="/images/GP/prediction.png" width="600px" class="center">}}



