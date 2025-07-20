# Smoothie Customization App

## 🥤Customizable Smoothie Ordering System🥤

An interactive web application that allows users to customize their smoothies by selecting fruits. The app fetches real-time nutritional data for each fruit and stores the user's smoothie order in a Snowflake database.

## Table of Contents

- Project Description

- Technologies Used

- Installation

- Usage

- Features

## Project Description

This project allows users to create their own custom smoothies by choosing from a list of fruits. The app integrates with Snowflake to retrieve available fruit options and store the smoothie orders. Nutritional data for each selected fruit is fetched through an external API to give the user more information about their smoothie ingredients.

## Technologies Used

- Streamlit: Framework for building interactive web applications.

- Snowflake: Cloud-based data warehousing for querying and storing smoothie orders.

- Snowpark Python: Used to interact with Snowflake from Python code.

- Pandas: Data manipulation and conversion.

- Requests: For making API calls to retrieve nutritional data for fruits.

- Python: Primary programming language for backend logic.

## Installation

### Prerequisites:

- Ensure that you have Python installed (preferably 3.7+).

- You will need a Snowflake account and access credentials.

- You must also have a Streamlit installation.

### Steps:
- Clone the repository

- Navigate to the project directory

- Create a virtual environment (optional but recommended)

- Activate the virtual environment:

- Install the required dependencies:

- Set up your Snowflake credentials:

## Usage

- Set up your Snowflake credentials:
  - In the code, ensure that your Snowflake connection details are configured correctly.

  - Update the st.connection("snowflake") section with your Snowflake account information.

- Run the Streamlit app:

- App Interaction:

  - Enter your name in the "Name on Smoothie" field.

  - Choose up to 5 fruits for your custom smoothie.

  - Click "Submit Order" to place your order, and your smoothie will be stored in Snowflake.

## Features

- Customizable Smoothies: Choose from a variety of fruits to create a personalized smoothie.

- Nutritional Data: Displays real-time nutrition information for each selected fruit from the external API.

- Database Integration: Smoothie orders are stored in Snowflake for future reference and analysis.

- Easy-to-Use Interface: Simple and interactive design using Streamlit.
