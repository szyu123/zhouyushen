---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year Ph.D. student in Econometrics and Statistics at the University of Chicago Booth School of Business, where I am advised by [Prof. Dacheng Xiu](https://dachxiu.chicagobooth.edu/). Prior to UChicago, I obtained a B.S. in Statistics from University of Science and Technology of China in 2020. My research lies in the intersection of econometrics, statistics, and machine learning, with a focus on addressing the methodological and theoretical challenges of applying machine learning techniques in economic contexts. I will be joining Peking University’s Guanghua School of Management in September 2025.

**Email**: zshen10@chicagobooth.edu

**[Download CV](_pages/CV.pdf)** 

## Research Interest
Machine Learning, High Dimensional Statistics, Time-series Econometrics, Financial Econometrics

## Working Paper

**[Deep Autoencoders for Nonlinear Factor Models: Theory and Applications](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5074409)** (with Dacheng Xiu)  
<span style="color:gray;">Working paper</span>

Abstract: Autoencoders are neural networks widely used for unsupervised tasks such as dimensionality reduction and feature extraction. This paper provides non-asymptotic guarantees for deep autoencoders under nonlinear factor models, showing they effectively recover latent components with diminishing errors as dimensionality and sample size increase. The extracted factors converge to the true latent factors, up to functional transformations. We further extend these results to supervised autoencoders, supporting their use in factor-augmented regression, matrix completion,
and panel regression with unobserved heterogeneity. Finally, we illustrate their economic applications in evaluating the causal impact of emissions regulation and predicting asset returns.



---

**[Can Machines Learn Weak Signals?](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4722678)** (with Dacheng Xiu)  
<span style="color:gray;">Working paper, winner of the 2024 Bates-White Prize for the Best Paper at SoFiE Annual Conference.</span>


Abstract: In high-dimensional regression scenarios with low signal-to-noise ratios, we assess the predictive performance of several prevalent machine learning algorithms. Theoretical insights show Ridge regression's superiority in exploiting weak signals, surpassing a zero benchmark. In contrast, Lasso fails to exceed this baseline, indicating its learning limitations. Simulations reveal that Random Forest generally outperforms Gradient Boosted Regression Trees when signals are weak. Moreover, Neural Networks with L_2-regularization excel in capturing nonlinear functions of 
weak signals. Our empirical analysis across six economic datasets suggests that the weakness of signals, not necessarily the absence of sparsity, may be Lasso's major limitation in economic predictions.

---

**Recurrent Neural Networks Meet Time Series: A Theoretical Perspective** (with Xiao Chen, Yu Chen, and Dacheng Xiu)  
<span style="color:gray;">Work in progress</span>

Abstract: Recurrent Neural Networks (RNNs) are a class of artificial neural networks designed to model sequential data, including text, speech, and time series. This paper investigates the internal mechanisms of RNNs and provides theoretical guarantees within the framework of time series models. Specifically, we analyze a nonlinear autoregressive and moving-average model  and derive a statistical error bound for RNN prediction performance. Our analysis demonstrates that RNNs excel at capturing nonlinear dependencies in noise, offering a distinct advantage over traditional nonparametric methods such as feed-forward neural networks.

---

**Boosting or Bagging? Navigating Weak Signals** (with Dacheng Xiu and Mingjie Zhang)  
<span style="color:gray;">Work in progress</span>

Abstract: This study investigates the predictive performance of Bagging and Boosting, two widely used ensemble techniques, in high-dimensional settings characterized by weak signals. Using a novel theoretical framework, we evaluate and compare their effectiveness. Our analysis demonstrates that Bagging excels at capturing weak signals, consistently outperforming the naive benchmark predictor. In contrast, Boosting often underperforms in these environments. Building on these insights, we propose modifications to the traditional random forest algorithm, enhancing its effectiveness for prediction tasks involving weak signals.

## Published Paper

**[Modeling Tail Index With Autoregressive Conditional Pareto Model](https://www.tandfonline.com/doi/abs/10.1080/07350015.2020.1832504)** (with Yu Chen and Ruxin Shi)  
<span style="color:gray;">Journal of Business & Economic Statistics, Volume 40, 2022</span>

Abstract: We propose an autoregressive conditional Pareto (AcP) model based on the dynamic peaks over threshold method to model a dynamic tail index in the financial markets. Unlike the score-based approach which is widely used in many articles, we use an exponential function to model the tail index process for its intuitiveness and interpretability. Probabilistic properties of the AcP model and the statistical properties of its parameter estimators of maximum likelihood are studied in this article. Real data are used to show the advantages of AcP, especially, compared to the estimation volatility of GARCH model, the result of AcP is more sensitive to turmoil. The estimated tail index of AcP can accurately reflect the risk of the stock and may even play an early warning role to the turmoil of stock market. We also calculate the tail connectedness based on the estimated tail index of AcP and show that tail connectedness increases during period of turmoil, which is consistent with the result of the score-based approach.

