#  Spotify Power BI Project
This project integrates Spotify's API with Power BI to create custom data visualizations. The script extracts album cover images from Spotify based on track information from a CSV file and enhances a Power BI report with these images. Here's how to set up and run the project.


![image](https://github.com/sonuf123/-/assets/24766030/63fa74a7-c940-4ff4-9c89-821f80cc0f3c)

##  Project Overview
Programming Language: Python

Libraries Used: requests, pandas

External Services: Spotify API

Purpose: Retrieve album cover images from Spotify based on track and artist names in a CSV file, and then display the most popular track's cover in a Power BI report.

 ##  Setup and Prerequisites
 
To run this project, you'll need to:

Obtain Spotify API credentials.

Install Python and necessary libraries.

Prepare a CSV file with track and artist information.

Set up a Power BI report to visualize the data.

##   Step 1: Get Spotify API Credentials

To interact with Spotify's API, you need a client ID and client secret.

Register your app at Spotify for Developers to get these credentials.

##   Step 2: Install Python Libraries

Ensure you have Python installed.

To install the required libraries, run:

<img width="247" alt="img1" src="https://github.com/sonuf123/-/assets/24766030/82f9d257-ec29-4d7c-8b62-5cd1fa551a06">

## Step 3: Prepare Your Data

Create or obtain a CSV file with the following columns:

track_name: The name of the track.

artist_name: The name of the artist.

Update the script with the correct CSV file path.

##  Step 4: Run the Python Script

<img width="545" alt="image" src="https://github.com/sonuf123/-/assets/24766030/fe6e341b-0c99-4381-89eb-f744a8aef9aa">
<img width="592" alt="image" src="https://github.com/sonuf123/-/assets/24766030/403b7ef0-bcb7-44ff-a82d-17b69e2b3eb7">

## Step 5: Integrate with Power BI
Use the updated CSV file to integrate with Power BI and use DAX formulas to display the correct image. 
The following HTML code snippet can be used to create a cropped image display in Power BI:

<img width="632" alt="image" src="https://github.com/sonuf123/-/assets/24766030/d59b047b-2a9f-4576-8a79-6f1e58a40473">


In this Power BI report, set the variable x to the URL of the most popular track's album cover to display it in the report.



