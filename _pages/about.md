---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year Ph.D. student in Econometrics and Statistics at the University of Chicago Booth School of Business, where I am advised by [Prof. Dacheng Xiu](https://dachxiu.chicagobooth.edu/). Prior to UChicago, I obtained a B.S. in Statistics from the School of the Gifted Young, University of Science and Technology of China in 2020. My research lies in the intersection of econometrics, statistics, and machine learning, with a focus on providing theoretical guarantees for applying machine learning methods in the field of economics and finance.

**Email**: zshen10@chicagobooth.edu

**[Download CV](_pages/CV.pdf)** 

## Research Interest
Machine Learning, High Dimensional Statistics, Time-series Econometrics, Financial Econometrics

## Research
**On the Theory of RNNs** (with Xiao Chen, Yu Chen, and Dacheng Xiu)  
<span style="color:gray;">Coming Soon</span>

Recurrent Neural Networks (RNNs) represent a class of artificial neural networks specifically designed to model sequential data, such as text, speech, and time series. This paper investigates the internal mechanisms of RNNs by providing theoretical guarantees within the framework of time series models. We analyze a nonlinear autoregressive and moving-average model (NARMA) and establish a statistical error bound for the prediction error of RNNs. The bound comprises two components: the approximation error, influenced by the smoothness of the target function and the dimensionality of the input, and the estimation error, governed by the architecture of the RNN and the mixing properties of the underlying process. In comparison to traditional nonparametric regression methods, RNNs are advantageous due to their ability to capture nonlinear dependencies within the noise effectively. The results from our simulation study demonstrate that RNNs outperform both Autoregressive Moving Average (ARMA) models and Deep Neural Networks (DNNs) in predictive performance.

---

**On the Theory of Deep Autoencoders** (with Dacheng Xiu)  
<span style="color:gray;">Coming Soon</span>

Autoencoders are pivotal in unsupervised machine learning, widely employed for dimension reduction, feature learning, and signal denoising. This study provides non-asymptotic guarantees for deep autoencoders within a nonlinear factor model framework. We demonstrate that deep autoencoders can effectively retrieve common components from model inputs. 
The associated error comprises a component that diminishes with increasing dimensionality---akin to the `blessings of dimensionality' observed in linear factor models---and another component that vanishes with an increasing sample size at the optimal nonparametric regression rate, as if the factors were directly observed. Furthermore, we show that the extracted factors converge to the true latent factors, albeit through a functional transformation. 


---

**[Can Machines Learn Weak Signals?](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4722678)** (with Dacheng Xiu)  
<span style="color:gray;">Working paper, winner of the 2024 Bates-White Prize for the Best Paper at SoFiE Annual Conference.</span>


In high-dimensional regression scenarios with low signal-to-noise ratios, we assess the predictive performance of several prevalent machine learning algorithms. Theoretical insights show Ridge regression's superiority in exploiting weak signals, surpassing a zero benchmark. In contrast, Lasso fails to exceed this baseline, indicating its learning limitations. Simulations reveal that Random Forest generally outperforms Gradient Boosted Regression Trees when signals are weak. Moreover, Neural Networks with L_2-regularization excel in capturing nonlinear functions of 
weak signals. Our empirical analysis across six economic datasets suggests that the weakness of signals, not necessarily the absence of sparsity, may be Lasso's major limitation in economic predictions.

---

**[Modeling Tail Index With Autoregressive Conditional Pareto Model](https://www.tandfonline.com/doi/abs/10.1080/07350015.2020.1832504)** (with Yu Chen and Ruxin Shi)  
<span style="color:gray;">Journal of Business & Economic Statistics, Volume 40, 2022</span>

We propose an autoregressive conditional Pareto (AcP) model based on the dynamic peaks over threshold method to model a dynamic tail index in the financial markets. Unlike the score-based approach which is widely used in many articles, we use an exponential function to model the tail index process for its intuitiveness and interpretability. Probabilistic properties of the AcP model and the statistical properties of its parameter estimators of maximum likelihood are studied in this article. Real data are used to show the advantages of AcP, especially, compared to the estimation volatility of GARCH model, the result of AcP is more sensitive to turmoil. The estimated tail index of AcP can accurately reflect the risk of the stock and may even play an early warning role to the turmoil of stock market. We also calculate the tail connectedness based on the estimated tail index of AcP and show that tail connectedness increases during period of turmoil, which is consistent with the result of the score-based approach.

