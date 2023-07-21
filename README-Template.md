# Simple Computational Models for Challenge 2

Rasteh is generating simple models using LM and LASSO models as proof of concept for contstants for challenge 2.

## Folders

There are 3 foldrs in this repository.

## data folder 
  including all the required data from each dataset used to train the model.
  
## result folder
  results for each dataset will be automatically saved in a subdirectory related to that dataset. 

## src folder
Is the folders that contains all the source codes. There are two files in that folder. They must be run in the order they are mentioned here. First we run LM_model and then LASSO model.

### LM_model.Rmd file that includes:

a) set up section: the place you set up information about dataset and required informations are compiled in this section

b) Load Data section: all the preprocessing, required normalization, transformation and encoding need to be done. 

c) three model approaches:
  1) Very trivial(no model):
    Just spearman correlation of ranked data between different pairs of predictors and tasks
    
  2) one predictor LM model:
    is a linear regression model that is trained by one predictor for each task
    
  3) multi predictor LM model:
    a linea regression that is trained based on different combination and number of predictors to predict each task
  
### LASSO_model.Rmd file that includes:
a) set up section: the place you set up information about dataset and required informations are compiled in this section

b) multi predictor LASSO model:
    a lASSO regression that is trained based on different combination and number of predictors to predict each task


