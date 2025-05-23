# API_INTEGRATION_AND_DATA_VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS PVT.LTD

*NAME*: AmolHanmantrao Shrirame

*INTERN ID*: CT06DM767

*DOMAIN*: B.Tech CSE (Computer Science and Engineering)

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

## DESCRIPTION

Goal: Fetch weather data from OpenWeatherMap API and visualize it using Python.

Prerequisites:

Python Installed: Make sure you have Python (preferably Python 3.x) installed on your system. You can download it from the official Python website.
Internet Connection: To access the OpenWeatherMap API.
________________________________________

Step 1: Obtain an OpenWeatherMap API Key
Go to OpenWeatherMap Website: Open your web browser and navigate to https://openweathermap.org/.
Sign Up/Log In: If you don't have an account, click on "Sign Up" and follow the registration process. If you already have an account, simply log in.
Access API Keys: Once logged in, click on your username (usually in the top right corner) and select "My API keys" from the dropdown menu.
Generate a Key (if needed): You should see a default API key. If you don't, or you want to generate a new one, you can do so on this page. Copy this API key; you'll need it in the next step.
________________________________________

Step 2: Set Up Your Python Environment
1.	Create a Project Folder: Create a new folder on your computer for this project (e.g., weather_dashboard).
2.	Open a Code Editor: Open your preferred code editor (like VS Code, Sublime Text, Atom, or even a simple text editor).
3.	Create a Python File: Inside your weather_dashboard folder, create a new file named weather_script.py (or any .py name you prefer).
________________________________________
Step 3: Install Required Python Libraries
1.	Open Terminal/Command Prompt: Navigate to your project folder (weather_dashboard) using your terminal or command prompt. 
o	On Windows: Open Command Prompt or PowerShell. Use cd path\to\your\weather_dashboard.
o	On macOS/Linux: Open Terminal. Use cd path/to/your/weather_dashboard.
2.	Install Libraries: Run the following command to install all the necessary libraries: 
Bash
pip install requests pandas matplotlib seaborn
This command will download and install the requests, pandas, matplotlib, and seaborn libraries.
________________________________________
Step 4: Add the Python Code
1.	Copy the Provided Code: Open the weather_script.py file you created in Step 2.
2.	Paste the Code: Paste the entire Python code you provided earlier into this file:
3.	Replace API Key: Crucially, find the line api_key = "5dfe1d2dd87128f61cdba9b8f1dcf9d8" and replace "5dfe1d2dd87128f61cdba9b8f1dcf9d8" with the actual API key you obtained in Step 1.
Example:
Python
api_key = "your_actual_api_key_goes_here"
4.	Optional: Change City: You can change the city_name variable to any city you want to fetch weather data for (e.g., "Mumbai", "Bangalore", "London").
________________________________________
Step 5: Run the Python Script
1.	Go to Terminal/Command Prompt: Make sure you are still in your weather_dashboard project folder in your terminal or command prompt.
2.	Execute the Script: Run the following command: 
python weather_script.py
________________________________________
Step 6: Observe the Output
1.	Console Output: You will see a JSON-formatted output of the fetched weather data printed in your terminal.
2.	Visualization Window: A new window will pop up displaying the bar plot of the current weather parameters (Temperature, Feels Like, Humidity, Pressure, Wind Speed) for the specified city.
3.	Confirmation Message: After the plot window closes (or if you close it), you'll see a confirmation message in your terminal: "Simple bar plot showing the main weather parameters has been generated."

*OUTPUT*:


![Image](https://github.com/user-attachments/assets/dbc354ad-98f3-417f-b64b-a195736b1030)

![Image](https://github.com/user-attachments/assets/47b12e02-833e-41ef-a32b-6dcbb7c72539)

![Image](https://github.com/user-attachments/assets/1a5ba8fe-e9f5-4d26-a0ab-01d6ef5611cf)
________________________________________



