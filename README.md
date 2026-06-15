# Movie Ratings Analysis with Polars

## Description
This project focuses on exploring and analyzing movie data using **Polars**, a high-performance data processing library. By leveraging the datasets `movies.csv`, `ratings.csv`, and `tags.csv`, this project demonstrates how to efficiently clean, manipulate, and extract insights from structured movie-related data.

## Project Overview
This analysis was developed using Google Colab and focuses on:
* **Data Loading and Inspection**: Efficiently loading large datasets.
* **Data Cleaning**: Handling missing values and ensuring data integrity.
* **Exploratory Data Analysis (EDA)**: Computing average ratings, genre distributions, and user activity metrics using Polars' high-performance syntax.

## Dataset Structure
The analysis is based on the following files:

* **movies.csv**: Contains `movieId`, `title`, and `genres` (a pipe-separated list).
* **ratings.csv**: Includes `userId`, `movieId`, `rating` (0.5 to 5.0), and `timestamp`.
* **tags.csv**: Consists of `userId`, `movieId`, `tag` (user-generated string), and `timestamp`.

## Goal
The primary objective of this project is to showcase the speed and capabilities of Polars in handling datasets, moving from initial data inspection to actionable analysis.

## How to Run
You can open the `polars_movie_analysis.ipynb` file directly in Google Colab or any Jupyter-compatible environment to explore the analysis process.

---
*Created by Turkhan Nabiyev*
