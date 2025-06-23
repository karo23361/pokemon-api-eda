# Pokémon API EDA
# 🧬 Pokémon API Data Analysis

This project analyzes Pokémon data fetched from the [PokeAPI](https://pokeapi.co/) using Python. It focuses on basic exploration and visualization of Pokémon characteristics such as height, weight, type combinations, and BMI-like metrics.

## 🚀 Project Overview

The notebook retrieves data on the first 1000 Pokémon using PokeAPI and performs data wrangling and visualization to explore patterns in their attributes. Key insights are derived based on:

- Distribution of height and weight
- Prevalence of single vs. dual-type Pokémon
- Common type combinations
- Type-based averages
- A Pokémon-style BMI comparison

## 🛠️ Technologies Used

- **Python**
- **Pandas** – data manipulation
- **Seaborn & Matplotlib** – visualization
- **Requests** – HTTP API calls
- **PokeAPI** – data source

# 📊 Key Analysis & Visualizations

## 🔝 Top 5 Tallest Pokémon
A horizontal bar chart highlighting the tallest Pokémon by height (in meters).

## ⚖️ Weight Distribution by Main Type
Boxplot showing how weight varies by primary type (e.g., Fire, Water, etc.).

## 🔁 Single vs Dual Type Pokémon
A donut-style pie chart showing the proportion of Pokémon with one or two types.

## 📐 Average Size by Type
A stylized table summarizing the mean height and weight for each primary type.

## 🔥 Most Common Type Combinations
A heatmap showing the most frequent type_1 and type_2 combinations (Top 5 of each).

## 🧮 Pokémon BMI Calculation
A simple BMI-like metric calculated from weight and height, identifying the Pokémon with the highest and lowest values.
