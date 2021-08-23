# Quantitative Asset & Risk Management I
Spring 2021 - HEC Lausanne

![alt text](https://camo.githubusercontent.com/c327657381291ed9f2e8866cb96ac4861431d9c244b7b14dcf4e1470cbf632da/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f612f61332f4845435f4c617573616e6e655f6c6f676f2e7376672f32393370782d4845435f4c617573616e6e655f6c6f676f2e7376672e706e67)

## Introduction

This repository contains all codes, papers and data for the projects achieved as part of the course "Quantitative Asset & Risk Management I".

## Project 1

This report aims to develop various types of optimal portfolios in the sense of Markovitz. The paper is separated into two parts. The first part will be about an optimal mean-variance portfolio allocation (i.e. EV allocation). The second part will be about an optimal mean-variance-skewness-kurtosis portfolio allocation (i.e. SK allocation). Our optimization methods will be based on the paper of E. Jondeau & M. Rockinger (2004) on Optimal Portfolio Allocation Under Higher Moments. The rationale of using a model which considers higher central moments is that we no longer assume that asset returns are normally distributed but that they exhibit an asymmetric and/or fat-tailed distribution. We, therefore, incorporate the third and fourth central moments into the investors’ utility function. Finally, we will compare the results of the EV and SK allocation.

Our data set includes the prices of the World Equities index, World Bonds, US high yield bonds, oil and gold, from 1999 to 2021). We have in total 1,104 observations for each asset. The data processing has been exclusively conducted on Python, using various libraries.

## Project 2

This report aims to develop a portfolio by designing an investment process that will combine a Strategic Asset Allocation (SAA) component with a Tactical Asset Allocation (TAA) com- ponent. The paper is separated into three parts. The first part will aim to create an SAA component through various types of optimizations. The second part will aim to create a TAA component, using long/short value and momentum factors, and developing a strategy using the VIX Index. The third and final part will aim to combine both models to create a model portfolio. As we will be restricted on our position on some assets, we will have to create a replication portfolio where its performance will be as close as possible to the model portfolio. We will present various performance measures such as the Sharpe ratio, maximum drawdown, hit ratio, tracking error, and information ratio throughout the parts.

Our data set includes 7 indices representing the monthly prices of world equities, world bonds, US investment-grade bonds, US high yield bonds, gold, energy and cooper, from 2000 to 2021 with a total of 247 observations per asset. The data processing has been exclusively conducted on Python, using various libraries.

## Project 3

This paper is an extension to the previous project 2 on portfolio allocation, focusing this time on core concepts of risk management. Managing risk is a fast-growing sector in which financial institutions are increasingly interested in understanding concepts and dynamics be- hind an investor’s biggest fear: losses. This report will describe various models and methods of risk assessment, which will then be applied to our three portfolios presented on the previous report, the Strategic Asset Allocation (SAA), the Tactical Asset Allocation (TAA) and the Real (Replication) Portfolio. Important concepts describing risks such as the Value at Risk (VaR) and the Expected Shortfall (ES) will be described and applied to practical portfolios. Finally, further analyses on the sources and consequences of risk will be made to give a global picture of risk in the past decade over a diversified range of seven assets. 
