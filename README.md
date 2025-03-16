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


## Exploratory Data Analysis (EDA)

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

- Brasil: Geothermal (565 768), Solar (547 306), Wind (526 767)
- Austrália: Geothermal (587,615), Biomass (519,512), Hydro (511 043)
- Canadá: Wind (569 573), Geothermal (556 750), Hydro (515 506)

- Is the energy transition truly cutting CO₂ emissions?
Interestingly, Australia records the highest average **CO₂ emissions** (0.53 Mt), while India has the lowest (0.45 Mt). Considering that India is both a leading investor in renewables and a top country in installed capacity, this suggests that a strong commitment to clean energy contributes to lower emissions.

**So, does investing in renewables make a difference?**
Based on this data, the answer seems to be yes. Countries that heavily invest in clean energy are not only increasing their installed capacity but also managing to keep emissions lower. While challenges remain, the numbers suggest that transitioning to renewables is more than just a trend—it’s a strategic move toward a cleaner, more sustainable future. 

<table>
  <tr>
    <th>Country</th>
    <th>Emissions 2000</th>
    <th>Emissions 2005</th>
    <th>Emissions 2010</th>
    <th>Emissions 2015</th>
    <th>Emissions 2020</th>
    <th>Emissions 2023</th>
    <th>Change 2000-2023 (%)</th>
    <th>Change 2020-2015 (%)</th>
    <th>Change 2020-2023 (%)</th>
  </tr>
  <tr>
    <td>Australia</td>
    <td>437142.43</td>
    <td>27898.53</td>
    <td>649566.59</td>
    <td>757429.62</td>
    <td>131626.70</td>
    <td>509298.60</td>
    <td>16.51</td>
    <td>-82.62</td>
    <td>286.93</td>
  </tr>
  <tr>
    <td>Brazil</td>
    <td>526527.36</td>
    <td>963457.77</td>
    <td>369447.56</td>
    <td>382920.92</td>
    <td>94519.39</td>
    <td>346001.96</td>
    <td>-34.29</td>
    <td>-75.32</td>
    <td>266.06</td>
  </tr>
  <tr>
    <td>Canada</td>
    <td>709200.05</td>
    <td>792319.92</td>
    <td>378519.69</td>
    <td>393533.18</td>
    <td>71474.34</td>
    <td>474930.86</td>
    <td>-33.03</td>
    <td>-81.84</td>
    <td>564.48</td>
  </tr>
  <tr>
    <td>China</td>
    <td>614841.74</td>
    <td>883655.78</td>
    <td>402397.77</td>
    <td>253938.60</td>
    <td>910615.66</td>
    <td>295417.08</td>
    <td>-51.95</td>
    <td>258.60</td>
    <td>-67.56</td>
  </tr>
  <tr>
    <td>France</td>
    <td>549105.36</td>
    <td>492200.97</td>
    <td>217082.03</td>
    <td>232158.03</td>
    <td>298153.53</td>
    <td>462873.80</td>
    <td>-15.70</td>
    <td>28.43</td>
    <td>55.25</td>
  </tr>
  <tr>
    <td>Germany</td>
    <td>325889.36</td>
    <td>319883.85</td>
    <td>763821.19</td>
    <td>77329.76</td>
    <td>54558.93</td>
    <td>59479.19</td>
    <td>-81.75</td>
    <td>-29.45</td>
    <td>9.02</td>
  </tr>
  <tr>
    <td>India</td>
    <td>704675.73</td>
    <td>65007.78</td>
    <td>437529.79</td>
    <td>340001.66</td>
    <td>139377.21</td>
    <td>167284.65</td>
    <td>-76.26</td>
    <td>-59.01</td>
    <td>20.02</td>
  </tr>
  <tr>
    <td>Japan</td>
    <td>11334.60</td>
    <td>454502.77</td>
    <td>840378.80</td>
    <td>833178.36</td>
    <td>525288.67</td>
    <td>991128.84</td>
    <td>8644.28</td>
    <td>-36.95</td>
    <td>88.68</td>
  </tr>
  <tr>
    <td>Russia</td>
    <td>387030.46</td>
    <td>45557.51</td>
    <td>932965.62</td>
    <td>389083.64</td>
    <td>912903.25</td>
    <td>317695.72</td>
    <td>-17.91</td>
    <td>134.63</td>
    <td>-65.20</td>
  </tr>
  <tr>
    <td>USA</td>
    <td>10503.88</td>
    <td>684123.84</td>
    <td>27931.47</td>
    <td>293952.14</td>
    <td>593925.98</td>
    <td>714962.63</td>
    <td>6706.65</td>
    <td>102.05</td>
    <td>20.38</td>
  </tr>
</table>

The table above allows us to **analyze how CO₂ emissions have evolved between 2000 and 2023 across different countries**. Comparing these changes can provide insights into the progress or setbacks in emission reduction policies. **These variations, reflected in the rise or fall of CO₂ emissions over the years, may indicate the effectiveness of policies implemented in each country to mitigate or halt climate change**.

**Countries with significant emission reductions, such as Germany and India, can serve as models for policies and investments in greener technologies. This can also help direct investments toward regions making the most significant progress.**

These data also help assess progress toward **Global Climate Goals**, such as those set by the **Paris Agreement**, which aims to **limit global warming**. By analyzing the countries with the highest emission growth, it is possible to evaluate where efforts need to be intensified.

- Sharp declines in some countries: Germany (-81.75%), India (-76.26%), and Canada (-33.03%) have significantly reduced emissions between 2000 and 2023.
- **Germany and France maintain a downward trend, which may be linked to effective environmental policies.**
- **Fluctuations in Brazil and Russia**: Both have reduced emissions in the long term but experienced peaks and drops, possibly indicating instability in their energy models.
- **Unexpected increases in Japan and the USA**: Japan (+8644.28%) and the USA (+6706.65%) have shown massive increases, which seem to be errors or indications of outlier data. The extreme percentage values (such as Japan and the USA) suggest possible data inconsistencies or drastic variations due to specific factors.
- **China alternates between growth and reduction, possibly due to its energy mix and industrialization.**


- How is the proportion of energy from renewable energy calculated in this dataset?
The dataset shows that Australia has an average renewable energy proportion of 52.72%, Germany 51.16%, and France 50.89%.

- According to my analysis of this dataset, countries like France, Russia, and India have **strong wind resources**, with average wind speeds of 7.75, 7.71, and 7.61 m/s, respectively, making wind energy a major part of their renewable portfolios. In contrast, Brazil and Australia benefit from high **solar irradiance**, leading to a stronger focus on solar energy, with average values of 206.06 and 201.71 W/m², respectively.
(**[see wind speed visualization](#wind)**) 
(**[see solar irradiance visualization](#solar-irradiance)**)


These results highlight the importance of continuing to invest in sustainable energy solutions. I invite you to explore these data further and reflect on how we can accelerate the transition to a more responsible energy future.


## Next Steps

- Expand the dataset to include additional renewable energy indicators
- Compare regional vs. global trends in clean energy investments
- Interactive Dashboard - Create an interactive version using a data visualization tool to make data exploration easier
- It would be important to confirm whether the values for Japan and the USA are correct or if there is an error in the data


## Contact

🔗 LinkedIn: [Ana Salsas](https://www.linkedin.com/in/anasalsas/)  
