US Bikeshare CLI Analyzer

A command-line application for exploring and analyzing US bikeshare data using Python.
This project allows users to interactively filter and analyze bike trip data by city, month, and day.

🚴Project Overview

The US Bikeshare CLI Analyzer is a Python-based data analysis tool that runs in the terminal.
It helps users understand bikeshare usage patterns across three major US cities:

Chicago

New York

Washington

Users can filter data by:

City

Month

Day of the week

And instantly receive statistics about:

Most common travel times

Popular stations and routes

Trip durations

User demographics

Dataset

The project uses three CSV files:

City	File
Chicago	chicago.csv
New York	new_york_city.csv
Washington	washington.csv

Each dataset contains information about:

Start and end times

Stations

Trip duration

User type

Gender (if available)

Birth year (if available)

Technologies Used

Python

Pandas – Data processing

Tabulate – Displaying tables in the terminal

▶How to Run the Program

Make sure Python is installed.

Install the required libraries:

pip install pandas tabulate


Run the program:

python bikeshare.py


Follow the instructions in the terminal:

Choose a city

Choose a month

Choose a day

The program will display the analysis results in a clean table format.

Features

Interactive user input (city, month, day)

Time statistics (most common month, day, hour)

Station statistics (start station, end station, most common trip)

Trip duration analysis

User demographics (user type, gender, birth year)

Option to display raw data in chunks

 Example Output
 Time Statistics
           +--------------------+-----------+
           | Item               | Value     |
           +--------------------+-----------+
           | Most common month  | March     |
           | Most common day    | Friday    |
           | Most common hour   | 17        |
           +--------------------+-----------+

Purpose

This project was created to demonstrate:

Data analysis skills

Working with real datasets

Python programming

Building interactive command-line applications

It is suitable for:

Data Science portfolios

Python practice

Learning data analysis workflows

👤 Author
MESHAL AHMAD

US Bikeshare CLI Analyzer Project
