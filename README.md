# Python Developer Job Scraping and Salary Analysis

## Table of Contents
- [Introduction](#introduction)
- [Tools Used](#tools-used)
- [Data Scraping](#data-scraping)
- [Data Cleaning](#data-cleaning)
- [Salary Analysis](#salary-analysis)
- [Graphical Visualization](#graphical-visualization)

## Introduction

This repository contains Python code for scraping job listings from "Indeed.com" with the keyword "Python developer." It also includes tools for data cleaning and the calculation of average salaries for Python developers across different cities. The final results are presented in graphical visualizations.

## Tools Used

The project utilizes the following tools and libraries:
- Python
- Selenium for web scraping
- Edge WebDriver for web automation
- NumPy for numerical calculations
- pandas for data manipulation
- Matplotlib for data visualization

## Data Scraping

The Python code uses Selenium and Edge WebDriver to scrape job listings from "Indeed.com." The extracted data includes details such as job titles, company names, locations, job types, salaries, and description links.

## Data Cleaning

The data extracted from the website is cleaned and processed using Python. This involves handling missing values, standardizing location names, and converting salary information into a consistent format.

## Salary Analysis

NumPy is used to calculate the average salary for Python developers across cities. The results are then sorted in descending order to identify the cities with the highest average salaries.

## Graphical Visualization

The average salary data is presented in a bar graph created using Matplotlib. The top 20 cities with the highest average salaries are displayed in the graph.
