# Quantitative Asset & Risk Management I
Spring 2021 - HEC Lausanne

![alt text](https://camo.githubusercontent.com/c327657381291ed9f2e8866cb96ac4861431d9c244b7b14dcf4e1470cbf632da/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f612f61332f4845435f4c617573616e6e655f6c6f676f2e7376672f32393370782d4845435f4c617573616e6e655f6c6f676f2e7376672e706e67)

## Introduction

This repository contains all codes, papers and data for the projects achieved as part of the course "Quantitative Asset & Risk Management I".

## Project 1

This report aims to develop various types of optimal portfolios in the sense of Markovitz. The paper is separated into two parts. The first part will be about an optimal mean-variance portfolio allocation (i.e. EV allocation). The second part will be about an optimal mean-variance-skewness-kurtosis portfolio allocation (i.e. SK allocation). Our optimization methods will be based on the paper of E. Jondeau & M. Rockinger (2004) on Optimal Portfolio Allocation Under Higher Moments. The rationale of using a model which considers higher central moments is that we no longer assume that asset returns are normally distributed but that they exhibit an asymmetric and/or fat-tailed distribution. We, therefore, incorporate the third and fourth central moments into the investors’ utility function. Finally, we will compare the results of the EV and SK allocation.

Our data set includes the prices of the World Equities index, World Bonds, US high yield bonds, oil and gold, from 1999 to 2021). We have in total 1,104 observations for each asset. The data processing has been exclusively conducted on Python, using various libraries.
