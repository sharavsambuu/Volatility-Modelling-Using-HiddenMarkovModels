# Volatility-Modelling-Using-HiddenMarkovModels
***Applying Hidden Markov Models to model Gold Intraday Volatility by detecting regime switches from low-volatility regimes to high-volatility***

> **Hidden Markov Models (HMMs) are a class of probabilistic graphical model that allow us to predict a sequence of unknown (hidden) variables from a set of observed variables. A > simple example of an HMM is predicting the weather (hidden variable) based on the type of clothes that someone wears (observed)."**

*https://medium.com/@postsanjay/hidden-markov-models-simplified-c3f58728caab#:~:text=Hidden%20Markov%20Models%20(HMMs)%20are,that%20someone%20wears%20(observed).*

The aim of this repository is to share with you my foray into volatility modelling using HiddenMarkovModels (HMM's.) HMM's were picked for this for their state nature. Markets have been shown to exist in regimes, states if you were, and if you can predict when a market is about to switch regime - say from low volatility to high volatility it can be monetized. This is what I have done within this repo. 

The data being modelled is the daily log returns of COMEX Micro-Gold Futures. The model aims to predict when the market will switch from low intraday returns (low volatility) to high intraday returns (high volatility) and graph this.

All data and notebooks are provided.

**Here is what the model outputs for the last circa 300 days of Daily Mini-Gold Futures Prices. As you can see highlighted in red are the clusters of high volatility.**

![Here you can see the clusters of volatility ](https://github.com/sweg44/Volatility-Modelling-Using-HiddenMarkovModels/blob/main/gold_volatility.jpeg)
