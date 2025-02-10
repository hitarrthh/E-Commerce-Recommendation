# E-Commerce Product Recommendation System

This project focuses on developing a product recommendation system for e-commerce platforms, utilizing machine learning techniques to enhance user experience by providing personalized product suggestions.

## Project Overview

The system is designed to analyze user behavior and product data to generate recommendations that are tailored to individual user preferences. This approach aims to increase user engagement and boost sales by presenting customers with products they are more likely to be interested in.

## Features

- **Data Analysis:** Utilizes datasets containing product reviews and ratings to understand user preferences.
- **Recommendation Algorithms:** Implements collaborative filtering and content-based filtering techniques to suggest products.
- **Web Application:** Provides a user-friendly interface for users to receive recommendations based on their interactions.

## Project Structure and Setup

Follow the steps below to understand the project structure and install the application on your local machine.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/hitarrthh/E-Commerce-Recommendation.git
   cd E-Commerce-Recommendation
   ```

2. **Project Structure:**
   ```
   app.py             # The main application file that runs the Flask web server
   recommend.ipynb    # A Jupyter Notebook containing the recommendation algorithm development and testing
   models/            # Directory containing trained models used for generating recommendations
   static/ and templates/  # Directories for static assets and HTML templates for the web application
   ecom_requirements.txt   # A file listing the Python dependencies required to run the project
   ```

3. **Create a Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. **Install Dependencies:**
   ```bash
   pip install -r ecom_requirements.txt
   ```

5. **Run the Application:**
   ```bash
   python app.py
   ```

Access the application at [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your web browser.

## Usage

- **Web Interface:** Interact with the web application to receive product recommendations based on user input and browsing history.
- **Notebook Exploration:** Use the `recommend.ipynb` notebook to explore the data analysis and recommendation algorithms in detail.


