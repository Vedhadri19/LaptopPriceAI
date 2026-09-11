# LaptopPriceAI

**Predict laptop prices instantly from specs using a trained machine learning model.**

A Streamlit web app that estimates the price of a laptop based on brand, type, RAM, weight, display features, CPU, storage, GPU, and operating system.

## Live Demo

🔗 [Click here to try the app](https://laptoppriceai-dng7xk563prmo9bkbgrv7x.streamlit.app/)  

## Features

- Simple and clean interactive UI
- Real-time price prediction in Indian Rupees (₹)
- Uses a full scikit-learn + XGBoost stacking pipeline
- Includes complete data analysis and model training notebook

## How It Works

1. Select laptop specifications (brand, RAM, CPU, GPU, screen size, etc.)
2. The app calculates PPI from resolution and screen size
3. Features are passed to a trained stacking model (RandomForest + GradientBoosting + XGBoost)
4. Model outputs log-price → converted to actual predicted price in ₹.

## Dataset
Public laptop dataset containing specifications and prices (primarily Indian market).

Key features engineered: Touchscreen, IPS, PPI, CPU brand, GPU brand, OS category, HDD/SSD.
