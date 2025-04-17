# Building a Spatially Explicit Deep Neural Network Model for Housing Price Prediction with Location Encoders

This project develops a **spatially explicit deep neural network (DNN)** model to predict housing prices across various locations in **California**. The model integrates traditional property-specific features with spatial and contextual information, leveraging location encoders to capture geographic variation.

## 🏠 Objective

To accurately predict housing prices by combining:
- **Property-specific features**: number of bedrooms, total rooms, house age, etc.
- **Contextual features**: geographic, socioeconomic, demographic, and environmental factors.

## 🧠 Method Overview

- A location encoder is used to embed spatial characteristics.
- Deep Neural Networks (DNNs) are applied to combine all input features.
- **Optuna** is used for hyperparameter tuning to optimize model performance.

## 📁 Project Setup

### 1. Clone the base repository

This project builds upon the [space2vec_demo](https://github.com/gengchenmai/space2vec_demo) repo:

```bash
git clone https://github.com/gengchenmai/space2vec_demo
cd space2vec_demo
