# EDA-Renewable-energy
- Exploratory data analysis on the impacts of different Weather conditions on Renewable Energy Generation

# About Dataset:
The dataset called "Solar_weather.csv" is a freely available collection of data on Kaggle that was gathered using the OpenWeatherMap API. The data was compiled by AI Maverick and provides a detailed analysis of the intricate correlation between weather conditions and the production of renewable energy. It contains hourly measurements of various weather parameters including solar radiation, temperature, humidity, and precipitation. Researchers and analysts can utilize this dataset to examine how weather patterns affect energy consumption and production.

#### The exploratory data analysis (EDA) conducted on the "Solar_weather.csv" dataset provides valuable insights into the impacts of different weather conditions on renewable energy generation. Here are some key findings:

- Energy Consumption Distribution: The histogram of energy consumption shows that the majority of entries (over 70%) lie in the 0-1000 Wh range. This suggests that a significant portion of energy consumption is relatively low.

- Energy Generation vs. Global Horizontal Irradiance (GHI): The scatter plot shows a direct proportional relationship between energy generation (Energy delta[Wh]) and GHI. As GHI increases, energy generation also tends to increase, indicating that solar radiation is a critical factor in energy generation.

- Temperature Impact: The scatter plot between temperature and energy consumption/generation reveals that energy consumption/generation decreases as the temperature drops below 0 degrees Celsius. This suggests that colder temperatures might affect renewable energy production.

- Monthly Energy Consumption: The bar plot comparing monthly average energy consumption/generation shows higher consumption/generation in the months of April, May, and June. This aligns with the intuition that warmer months have more solar radiation, leading to increased energy production from solar sources.

- Hourly Temperature and Energy Consumption: The line plot comparing hourly average temperature and energy consumption/generation indicates that energy consumption/generation is higher during specific hours of the day, possibly corresponding to peak energy demand periods.

- Wind Speed: The average wind speed per hour shows a fluctuating pattern throughout the day, which might suggest variations in wind energy generation potential.

# Conclusion
**1.More than 70% of energy consumption is lie between 0-1000 Wh.<br>
2.The Energy delta [Wh] and GHI is directly proportional to each other.<br>
3.Temperature is one of the key factors when compared with energy consumption/generation.<br>
4.Monthly consumption/generation of energy is more in months of April, May, June followed by March, July, August, September and least in October, November, December, & January.<br>
5.When we compare the monthly average temp with monthly average consumption despite of low temperature in Feb, Mar & Apr we noticed high consumption.**
