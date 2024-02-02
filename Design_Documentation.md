# Design and Process

#### By Justin Covach

## Objective

To create a deep learning model to learn from replay data the type of inputs the player would perform. Then once the model is trained with that data, create a system to actively play the game using the model.

### Requirements:

The process of development will go as follows:

- Program Setup
- Data retrieval
- Feature Collection & Regularization
- Model Creation & Design
- Model Training
- Optimizing the Model and Testing
- Use model in playing realtime

## Data Retrieval

Data will be retrieved using rocket league's replay system and parsed using a rocket league replay parser. This data will then be opened by the python file and read into the feature collection.

## Feature Collection & Regularization

#### Collection:

The data incoming will not all need to be fed into the learning model.
Available features are:

The features that will be used to train the model are:

The program will need to filter out these features and structure them in a matrix to be fed into the regularization.

#### Regularization:

This program will use z-score normalization so that the values are easily readable and mimic the continuous nature of the incoming data as they can be both positive and negative data.

This regularized data is the data that will be passed into the learning model.

## Model Creation & Design:

...

## Model Training

...

## Optimizing the Model and Testing

...

## Use model in playing realtime

...
