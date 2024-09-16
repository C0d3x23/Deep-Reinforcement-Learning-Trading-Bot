# Crypto Reinforcement Learning Trading Bot (PPO)

## Overview

This repository contains a work-in-progress project focused on building a Reinforcement Learning (RL) agent for trading stocks using historical market data. The project leverages the OpenAI Gym environment, custom-built environments for trading, and the Stable Baselines3 library for RL. The goal is to train a model to predict and make trading decisions based on historical stock prices and other financial indicators.

## Project Structure

- **Data Preparation**: Load and preprocess historical stock data.
- **Custom Environment**: Define a custom trading environment using Gym.
- **Model Training**: Train a reinforcement learning model using Stable Baselines3.

## Files and Directories

- `main.ipynb`: Main script to prepare data, define the environment, and train the model.
- `model/Log`: Directory for TensorBoard logs.

## Dependencies
Current dependencies being used are 

- `gymnasium`: For creating and managing the trading environment.
- `gym_anytrading`: Custom environments for trading tasks.
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `stable_baselines3`: For reinforcement learning models.
- `matplotlib`: For plotting and visualization.
- `scikit-learn`: For data scaling and preprocessing.

## Screenshots

Here are some screenshots of the project's progress:

### Current Explained Variance
 Base on what I currently know, an explained variance close to 1, the better. Based on this screenshot, my current model in training
peak value is at 0.3 which is very low. I also noticed that the chart shows instability.

![screenshot 1](https://github.com/user-attachments/assets/101970b4-3e6d-4798-a4be-8a2405d2f4d8)

### Current Value Loss
![screenshot 2](https://github.com/user-attachments/assets/1cfb6f49-8089-41dd-a7a7-8830af74765d)


Note: As of this writing the model is is still in training. 
