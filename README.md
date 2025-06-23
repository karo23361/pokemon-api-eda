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

![image](https://github.com/user-attachments/assets/ddb02011-fb52-4847-a43b-6a5a373ba48f)


The tallest Pokémon in the dataset are:

- Eternatus – 20.0 meters
  
![image](https://github.com/user-attachments/assets/ce3cc826-d277-4182-b6ea-28886426d3a5)

- Wailord – 14.5 meters
  
![image](https://github.com/user-attachments/assets/e3420af0-ff6a-447d-bfc6-2c0670701f79)

- Dondozo – 12.0 meters
  
![image](https://github.com/user-attachments/assets/4690023e-91f2-45eb-9487-4260ede893c6)

- Steelix – 9.2 meters
  
![image](https://github.com/user-attachments/assets/32bf7418-afef-464d-b6a6-18e46273db2f)

- Celesteela – 9.2 meters
  
![image](https://github.com/user-attachments/assets/a8fc5df0-4883-4e7c-9c21-a26940cbbd04)

These extreme values are mostly attributed to Legendary or massive aquatic Pokémon, whose design often emphasizes size for visual impact or lore.

## ⚖️ Weight Distribution by Main Type

The boxplot reveals significant variability in weight across different primary types:

![image](https://github.com/user-attachments/assets/db22b9c7-ad44-402e-98d5-0eb936a88765)


- Steel, Ice, and Dragon types have broader distributions and higher upper outliers, indicating that Pokémon of these types tend to be heavier overall.
- Fairy, Flying, and Bug types show tighter distributions, clustering closer to the median — these types generally include smaller, lighter species.
- Several types (e.g. Steel, Dragon) contain extreme outliers, hinting at the presence of a few extraordinarily heavy Pokémon, which skews the perception of their weight class.

This analysis is useful in understanding how physical design correlates with type classification in game design.

## 🔁 Single vs Dual Type Pokémon
A donut-style pie chart showing the proportion of Pokémon with one or two types.

![image](https://github.com/user-attachments/assets/d62f947e-b836-4fe7-8fbe-9950da1643d1)


- Single type: 49.7%
- Dual type: 50.3%

The distribution is nearly even, indicating that dual-typing is a core design philosophy in the Pokémon universe. Dual-type Pokémon often offer more complex gameplay dynamics, allowing for richer strategy in battles.

## 📐 Average Size by Type

A stylized table summarizing the mean height and weight for each primary type.

![image](https://github.com/user-attachments/assets/ad1e7db2-2e21-4a97-a520-720205ecb3b7)


By calculating mean height and weight per primary type, we observed:

- Steel, Ice, Ground, Rock, and Dragon types have the highest average physical dimensions.
- Fairy Pokémon stand out with the lowest average height and weight — reinforcing their theme as nimble, magical creatures.
- Notably, some types (like Fire and Electric) maintain mid-to-high average height but lower average weight, which may reflect design emphasis on agility or speed.

This shows how each type carries a thematic and physical identity beyond combat traits.

## 🔥 Most Common Type Combinations
A heatmap showing the most frequent type_1 and type_2 combinations (Top 5 of each).

![image](https://github.com/user-attachments/assets/044fc641-0563-4aa5-9063-bd365b38cbb4)


Some type combinations occur significantly more often:

- Normal–Flying: 27 Pokémon
- Grass–Poison: 14 Pokémon
- Bug–Flying: 13 Pokémon
- Bug–Poison: 11 Pokémon

Meanwhile, some combinations were completely absent in the dataset:
- Fire–Fairy: 0 Pokémon
- Normal–Poison: 0 Pokémon

This illustrates patterns in type-pairing logic. Common pairs often come from early-game or classic Pokémon, while rare combinations may be limited due to balance constraints or lore decisions.

## 🧮 Pokémon BMI Calculation
A pseudo-BMI metric (weight / height²) was used to compare body mass relative to size.

- 🪨 Highest BMI: Cosmoem — ~99,999

![image](https://github.com/user-attachments/assets/6cc62402-4e2a-4cc2-9db0-829ab69d255e)


Despite being only 0.1 meters tall, Cosmoem weighs 999.9 kg. This is likely intentional, symbolizing its dense, dormant form during evolution — making it a clear outlier and a great example of lore affecting data.

- 👻 Lowest BMI: Haunter — ~0.039

![image](https://github.com/user-attachments/assets/bfeb67b8-3464-48b2-a6c2-4ba8bf138c55)


Haunter, being a Ghost-type, is characterized by its gas-like, intangible body. This low value aligns with its design and lore — it's practically weightless despite having volume.



