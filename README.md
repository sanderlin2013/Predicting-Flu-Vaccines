# Predicting Flu Vaccine Compliance
## Overview

In 2009 the CDC gathered information on vaccine compliance in the U.S. using the National 2009 H1N1 Flu Survey. The **CDC** now wants to pull out **useful features** along with any other insights from this data to inform the creation of **a new survey** about COVID-19 vaccine compliance. 

## Business and Data Understanding

### Business Problem
Create a model that best predicts who gets the seasonal flu vaccine, so we can find the features relevant to routine vaccine compliance.

### Data

#### Limitations of the Dataset
The data was collected via telephone surveys, a commonly used polling method which is not representative or random (as people choose to respond or not when they are called). Additionally, new surveys and models may need to take into account the anti-vaccine movement (article [here](https://pubmed.ncbi.nlm.nih.gov/16039769/)) which was not as prevalent when the data was collected in 2009, as well as the cultural and behavioral shifts that have occurred due Covid-19. Finally, this dataset has a large amount of missing responses that need to be dealt with in order to model the data. We will discuss this in depth later on in the notebook. 
#### Why We Used This Dataset
Despite the above limitations, the National 2009 H1N1 Flu Survey contains a large number of responses, takes into account a large number of features relevant to seasonal flu vaccine compliance, and is a relatively recent dataset. For all these reasons, we decided to use this dataset to create our predictive model. 
#### Dataset Size 
The initial dataset contained was 26,707 responses with 36 questions. Only 27 questions were included in the analysis, as questions about the H1N1 vaccine or with responses containing identifying information were excluded. 


