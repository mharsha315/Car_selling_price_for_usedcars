# Car Selling Price Prediction

A Django web application that predicts the selling price of a car based on various features like car name, year, mileage, engine power, and more. The project includes a trained machine learning model to estimate the car's selling price using data processing libraries.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)


## Overview

This project utilizes machine learning to predict the selling price of a used car. It allows users to input car details through a web interface and returns an estimated selling price.

## Features

- Predicts the selling price of a car based on user inputs.
- User-friendly web interface built with Django and HTML/CSS.
- Uses a trained machine learning model with Scikit-learn.
- Handles different car attributes like mileage, engine power, fuel type, and more.

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
   ```bash
   git clone <your-repository-url>
   cd car-selling-price-prediction
2. ### Install Dependencies
- Ensure Python 3.7.10 is installed (as specified in `runtime.txt`).
- Install the dependencies from `requirements.txt`:
  ```bash
  pip install -r requirements.txt
3. ### Set Up the Database
- Run the following command to create the necessary tables in the SQLite database:
  ```bash
  python manage.py migrate
4. ### Run the Application
- Start the Django development server:
  ```bash
  python manage.py runserver


  
