# **Renewable Energy Data Analysis**

In recent years, we have witnessed a revolution in the energy sector. The climate crisis and the need for energy independence have driven countries to invest more and more in renewable energy. The goal? To **reduce CO₂ emissions, transition away from fossil fuels, and secure a sustainable future**.

Global agreements, such as the **Paris Agreement** represent a collective commitment to fighting climate change, setting ambitious targets for **2030** and **2050**. But are these efforts truly transforming our energy system?

## **Key Questions We Need to Answer:**
 - Are we significantly reducing CO₂ emissions?
 - Is the renewable energy sector creating more jobs?
 - Are countries increasing their installed capacity of clean energy?

To answer these questions and better understand this transition, I analyzed **renewable energy data from the past two decades**. Below, I share key insights that reveal how far we’ve come and where we’re heading in the pursuit of a cleaner future.

## Table of Contents
- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Technologies Used](#technologies-used)
- [Key Research Questions](#key-research-questions)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Visualizations](#visualizations)
- [Main Conclusions](#main-conclusions)
- [Next Steps](#next-steps)
- [Contact](#contact)


## Objective
This project aims to analyze **publicly available renewable energy data** to uncover  insights on:
- Employment in the renewable energy sector;
- Investments in clean energy;
- Types of renewable energy used across different countries.

By studying data from 2000 to 2023, we can **track global trends** and evaluate the progress made toward sustainability goals.

## Dataset Overview

- 📅 Time Range: 2000 - 2023

Key Variables:
- **Country**: Name of the country
- **Year**: Year of the data record
- **Renewable Energy Jobs**: Number of jobs in the renewable energy sector
- **Investments (USD)**: Investment in renewable energy in USD
- **CO2 Emissions**: CO₂ emissions in metric tons

📥 **Data Source:** This dataset was obtained from Kaggle. 
You can access it here: [Global Renewable Energy and Indicators Dataset](https://www.kaggle.com/datasets/anishvijay/global-renewable-energy-and-indicators-dataset/data).


## Technologies Used

- Data Cleaning: Pandas, NumPy
- Data Visualization: Matplotlib, Plotly
- Version Control: Git/GitHub

## Key Research Questions

- What types of renewable energy exist in each country?

# Energy Types by Country

<font size="2">
<table>
  <tr>
    <th>Country</th>
    <th>Energy Type</th>
    <th>Num of Energy Types</th>
  </tr>
  <tr>
    <td>Australia</td>
    <td>[Geothermal, Hydro, Solar, Biomass, Wind]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Brazil</td>
    <td>[Geothermal, Solar, Wind, Hydro, Biomass]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Canada</td>
    <td>[Biomass, Wind, Geothermal, Solar, Hydro]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>China</td>
    <td>[Solar, Biomass, Wind, Geothermal, Hydro]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>France</td>
    <td>[Biomass, Solar, Geothermal, Hydro, Wind]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Germany</td>
    <td>[Wind, Biomass, Geothermal, Solar, Hydro]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>India</td>
    <td>[Wind, Hydro, Solar, Biomass, Geothermal]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Japan</td>
    <td>[Biomass, Solar, Wind, Hydro, Geothermal]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Russia</td>
    <td>[Solar, Hydro, Biomass, Wind, Geothermal]</td>
    <td>5</td>
  </tr>
  <tr>
    <td>USA</td>
    <td>[Solar, Wind, Hydro, Biomass, Geothermal]</td>
    <td>5</td>
  </tr>
</table>
</font>

It’s no surprise that the same energy sources appear frequently, as renewables are available in all countries. Their adoption mainly depends on natural resource availability.

⚡ **Renewable Energy Sources & Capacity**
- What types of renewable energy are used in each country?
- What is the average installed capacity per country?

💰 **Investments in Renewable Energy**
- What is the total investment per country and per year?
- What is the average investment per country?

👷 **Employment in the Sector**
- What is the average number of jobs in renewable energy per country?

🌍 **Environmental Impact**
- Are CO₂ emissions decreasing in response to the energy transition?


##Exploratory Data Analysis (EDA)

- Descriptive statistics of key variables
- Time-series analysis to identify long-term trends

## Visualizations

### Installed Capacity
![Installed Capacity](https://raw.githubusercontent.com/anasalsas/renewable-energy-analysis/main/installed_capacity.png)

### Investment Trends
![Investment Trends](https://raw.githubusercontent.com/anasalsas/renewable-energy-analysis/main/investment_trends.png)

### Average Renewable Energy Jobs by Country and Energy Type
![Average Renewable Energy Jobs by Country and Energy Type](https://raw.githubusercontent.com/anasalsas/renewable-energy-analysis/main/jobs_by_RW_by_Country.png)

### CO₂ Emissions by Year and Country
![CO₂ Emissions by Year and Country](https://raw.githubusercontent.com/anasalsas/renewable-energy-analysis/main/CO2_Emissions_Year_Country.png)

### Average Proportion of Energy from Renewables (%)
![Average Proportion of Energy from Renewables (%)](https://raw.githubusercontent.com/anasalsas/renewable-energy-analysis/main/Avg_Proportion_RE.png)

### Wind Speed {#wind}
![Average Wind Speed by Country](https://raw.githubusercontent.com/anasalsas/renewable-energy-analysis/main/wind.png)

### Solar Irradiance {#solar-irradiance}
![Average Solar Irradiance by Country](https://raw.githubusercontent.com/anasalsas/renewable-energy-analysis/main/solar_irradiance.png)


## Main Conclusions:

Over the past two decades, the renewable energy sector has undergone significant transformations. But which countries are leading the way? And is the shift to clean energy really making an impact? Let’s break it down.

- Who has the highest installed capacity?
**India, France, and Germany top the list**, with installed capacities of **26 075.53 MW, 26 044.69 MW, and 25 667.94 MW, respectively**. These numbers reflect a strong commitment to scaling up renewable energy.
(**[see installed capacity visualization](#installed-capacity)**)

- Who is investing the most?
When it comes to financial commitment, **India leads with $5.27 billion in average annual investments**, closely followed by the USA with $5.24 billion. This raises an important question: is heavy investment directly linked to higher capacity and lower emissions?

- Where are the most jobs being created?
The transition to renewables is also reshaping the job market. The top three countries with **the highest average number of renewable energy jobs are Brazil (523 578), Australia (518 076), and Canada (515 524)** — all with close figures, highlighting a global effort to create green employment opportunities.

Beyond just looking at jobs per country, I wanted to dive deeper—where exactly are these jobs being created? Are some types of renewable energy generating more employment than others? By analyzing the data, clear patterns emerged. In Brazil, most jobs are concentrated in geothermal, solar, and wind energy. Meanwhile, in Australia, the leading sectors for employment are geothermal, biomass, and hydro. And in Canada, the top three are wind, geothermal, and hydro. These insights help us understand not only which countries are investing in renewables but also which technologies are driving the green job market.

- Brasil: Geothermal (565,768), Solar (547,306), Wind (526,767)
- Austrália: Geothermal (587,615), Biomass (519,512), Hydro (511,043)
- Canadá: Wind (569,573), Geothermal (556,750), Hydro (515,506)


- Are CO₂ emissions decreasing?
Interestingly, Australia records the highest average **CO₂ emissions** (0.53 Mt), while **India has the lowest (0.45 Mt)**. Given that India is also the top investor and one of the leaders in installed capacity, this suggests that a strong push for renewables pays off in reducing emissions.

**So, does investing in renewables make a difference?**
Based on this data, the answer seems to be yes. Countries that heavily invest in clean energy are not only increasing their installed capacity but also managing to keep emissions lower. While challenges remain, the numbers suggest that transitioning to renewables is more than just a trend—it’s a strategic move toward a cleaner, more sustainable future. 

- How is the proportion of energy from renewable energy calculated in this dataset?
The dataset shows that Australia has an average renewable energy proportion of 52.72%, Germany 51.16%, and France 50.89%.

- According to my analysis of this dataset, countries like France, Russia, and India have **strong wind resources**, with average wind speeds of 7.75, 7.71, and 7.61 m/s, respectively, making wind energy a major part of their renewable portfolios. In contrast, Brazil and Australia benefit from high **solar irradiance**, leading to a stronger focus on solar energy, with average values of 206.06 and 201.71 W/m², respectively.
(**[see wind speed visualization](#wind)**) 
(**[see solar irradiance visualization](#solar-irradiance)**)


## Next Steps

- Expand the dataset to include additional renewable energy indicators
- Compare regional vs. global trends in clean energy investments
- Interactive Dashboard - Create an interactive version using a data visualization tool to make data exploration easier


## Contact

🔗 LinkedIn: [Ana Salsas](https://www.linkedin.com/in/anasalsas/)  
