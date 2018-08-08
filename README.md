# data_fusion

This repo contains code for the examples in the Feit and Bradlow (chapter on Fusion Modeling)[] in the *Handbook of Marketing Research*. 

## Chapter abstract
This chapter introduces readers to applications of data fusion in marketing from a Bayesian perspective.  We will discuss several applications of data fusion including the classic example of combining data on media viewership for one group of customers with data on category purchases for a different group, a very common problem in marketing. While many missing data approaches focus on creating ``fused'' data sets that can be analyzed by others, we focus on the overall inferential goal, which, for this classic data fusion problem is to determine which media outlets attract consumers who purchase in a particular category and are therefore good targets for advertising. The approach we describe is based on a common Bayesian approach to missing data, using data augmentation within MCMC estimation routines.  As we will discuss, this approach can also be extended to a variety of other data structures including mismatched groups of customers, data at different levels of aggregation and more general missing data problems that commonly arise in marketing. This chapter provides readers with a step-by-step guide to developing Bayesian data fusion applications, including an example fully-worked out in the Stan modeling language.  Readers who are unfamiliar with Bayesian analysis and MCMC estimation may benefit by reading the chapter in this handbook on Bayesian Models first.


## Running the code
To run the examples from the chapter, first install the (R language)[] and (RStan)[https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started], which is the R interface to Stan.  (RStudio)[www.rstudio.com) is also recommended. After those are installed, you should be able to open (`Data_Fusion.R')[] and run the examples in the chapter. 
