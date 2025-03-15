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
- Investiments in clean energy;
- Types of renewable energy used across different countries.

By studying data from 2000 to 2023, we can **track global trends** and evaluate the progress made toward sustainability goals.

## 📂 **Dataset Overview**

- 📅 Time Range: 2000 - 2023

Key Variables:
- **Country**: Name of the country
- **Year**: Year of the data record
- **Renewable Energy Jobs**: Number of jobs in the renewable energy sector
- **Investments (USD)**: Investment in renewable energy in USD
- **CO2 Emissions**: CO₂ emissions in metric tons

📥 **Data Source:** This dataset was obtained from Kaggle. 
You can access it here: [Global Renewable Energy and Indicators Dataset](https://www.kaggle.com/datasets/anishvijay/global-renewable-energy-and-indicators-dataset/data).


## 🛠 **Technologies Used**

- Data Cleaning: Pandas, NumPy
- Data Visualization: Matplotlib, Plotly
- Version Control: Git/GitHub

## 🔍 **Key Research Questions**

- What types of renewable energy exist in each country?

# Energy Types by Country

| Country  | Energy Type                                                       | Num of Energy Types |
|----------|-------------------------------------------------------------------|----------------------|
| Australia| [Geothermal, Hydro, Solar, Biomass, Wind]                         | 5                    |
| Brazil   | [Geothermal, Solar, Wind, Hydro, Biomass]                         | 5                    |
| Canada   | [Biomass, Wind, Geothermal, Solar, Hydro]                         | 5                    |
| China    | [Solar, Biomass, Wind, Geothermal, Hydro]                         | 5                    |
| France   | [Biomass, Solar, Geothermal, Hydro, Wind]                         | 5                    |
| Germany  | [Wind, Biomass, Geothermal, Solar, Hydro]                         | 5                    |
| India    | [Wind, Hydro, Solar, Biomass, Geothermal]                         | 5                    |
| Japan    | [Biomass, Solar, Wind, Hydro, Geothermal]                         | 5                    |
| Russia   | [Solar, Hydro, Biomass, Wind, Geothermal]                         | 5                    |
| USA      | [Solar, Wind, Hydro, Biomass, Geothermal]                         | 5                    |

It’s no surprise that the same energy types appear frequently since renewable energies are available across all countries, regardless of dependency, as it relates to nature’s availability.

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


## 📊 **Exploratory Data Analysis (EDA)**

- Descriptive statistics of key variables
- Time-series analysis to identify long-term trends

## 📈 **Visualizations**

![Installed Capacity](https://github.com/anasalsas/renewable-energy-analysis/blob/main/installed_capacity.png)

![Investment Trends](https://github.com/anasalsas/renewable-energy-analysis/blob/main/investment_trends.png)

![CO₂ Emissions by Year and Country](https://github.com/anasalsas/renewable-energy-analysis/blob/main/CO2_Emissions_Year_Country.png)


## 📌 **Main Conclusions:**

Over the past two decades, the renewable energy sector has undergone significant transformations. But which countries are leading the way? And is the shift to clean energy really making an impact? Let’s break it down.

- Who has the highest installed capacity?
**India, France, and Germany top the list**, with installed capacities of **26 075.53 MW, 26 044.69 MW, and 25 667.94 MW, respectively**. These numbers reflect a strong commitment to scaling up renewable energy.

- Who is investing the most?
When it comes to financial commitment, **India leads with $5.27 billion in average annual investments**, closely followed by the USA with $5.24 billion. This raises an important question: is heavy investment directly linked to higher capacity and lower emissions?

- Where are the most jobs being created?
The transition to renewables is also reshaping the job market. The top three countries with **the highest average number of renewable energy jobs are Brazil (523 578), Australia (518 076), and Canada (515 524)** — all with close figures, highlighting a global effort to create green employment opportunities.

- Are CO₂ emissions decreasing?
Interestingly, Australia records the highest average **CO₂ emissions** (0.53 Mt), while **India has the lowest (0.45 Mt)**. Given that India is also the top investor and one of the leaders in installed capacity, this suggests that a strong push for renewables pays off in reducing emissions.

**So, does investing in renewables make a difference?**
Based on this data, the answer seems to be yes. Countries that heavily invest in clean energy are not only increasing their installed capacity but also managing to keep emissions lower. While challenges remain, the numbers suggest that transitioning to renewables is more than just a trend—it’s a strategic move toward a cleaner, more sustainable future. 

## 📌 **Next Steps**

- Expand the dataset to include additional renewable energy indicators
- Compare regional vs. global trends in clean energy investments
- Interactive Dashboard - Create an interactive version using a data visualization tool to make data exploration easier

### 📧 **Contact me**  

🔗 LinkedIn: [Ana Salsas](https://www.linkedin.com/in/anasalsas/)  
