# Smart Forecaster

Welcome to Smart Forecaster, a Python script that implements a basic login system for a system called "SmartForecaster." This script provides an interactive and secure environment for users to manage forecasting and historical data.

## Files

- **Users.csv:** CSV file containing user credentials for the login system.
- **DATA.xlsx:** Excel file storing historical data and serving as the primary data source.

## Description

This Python script introduces a secure login system for SmartForecaster, leveraging libraries such as csv for user credential management and getpass for secure password input. The login process initializes with a False status and prompts users for their username and password.

Upon successful login, users are granted access to the SmartForecaster system and presented with options for forecasting, updating historical data, and logging out.

### Forecasting

For forecasting, users input arrival data over a 7-day period. The script processes this data, compares it with historical data, and calculates expected staff requirements for each shift. Interactive editing of expected staff values is supported, and the final results, including expected staff numbers and associated labor expenses, are presented and saved to an Excel file.

### Updating Historical Data

The updating option allows users to upload a new dataset to supplement historical data, ensuring the system stays up-to-date. The script reads the new data, aligns it with existing historical data, and exports the merged dataset back to the "DATA.xlsx" file.

This script provides a user-friendly and secure solution for managing forecasting and historical data within the SmartForecaster system. It emphasizes data security by handling sensitive information locally and avoiding reliance on external platforms.

Feel free to explore and utilize this script to enhance the usability and reliability of your SmartForecaster system.
