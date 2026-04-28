# HUMAN DEVELOPMENT IN NIGERIA
## INTRODUCTION
The Human Development Index (HDI) is a composite statistical measure developed by the United Nations Development Programme to evaluate and compare countries' overall levels of human development.
Unlike purely economic indicators, HDI captures development as a multidimensional concept, focusing on the extent to which people can live long, knowledgeable, and economically secure lives.
<img width="819" height="573" alt="image" src="https://github.com/user-attachments/assets/6f03b596-c749-44dc-8dd8-800e2935a5c4" />



## PROBLEM STATEMENT 
An interactive dashboard was developed to review the stakeholder question: how has Nigeria’s human development changed over time, and which economic or social indicators explain the most significant improvements or constraints?
The dashboard was created to enable stakeholders:
- Monitor development trends over time.
- Find key drivers for HDI growth.
- Evaluate trade-offs between population, income, and welfare.
- Support evidence-based policy and strategic decision-making.
  
The analysis generates data-driven insights into long-term development patterns, key drivers of human development, and structural challenges affecting progress.

## DATA GATHERING
The data source is a time series spanning 64 years (1960–2023) with 200+ development indicators, sourced from the World Bank and the United Nations Development Programme. The dataset consists of a wide range of economic indicators, Health indicators, Education metrics, and Infrastructure and welfare variables.

## DATA CLEANING
To ensure analytical accuracy and usability, the dataset was processed using Excel Power Query.
<img width="975" height="566" alt="image" src="https://github.com/user-attachments/assets/f0bb6f18-2104-4b71-9369-1117adcf5464" />

- Conducted data profiling to assess data types, missing values and column consistency.
- I checked for duplicate entries, blank/null values to ensure consistency across indicators.
  
## DATA TRANSFORMATION
The original format was in Wide format (years as columns) 
- Unpivoted columns into long format to enable time-series analysis and for easier visualization and measures on Power BI
- To avoid dashboard clutter and improve analytical clarity, key indicators were filtered across four core dimensions:
  - Economic Indicators
  - Health Indicators
  - Education
  - Welfare &Infrastructure


KEY INSIGHTS

1.	HDI has improved, but progress is slow and incremental; it has increased from 0.38 (1990) → 0.56 (2023), a total change of +0.18 over ~33 years and an annual average growth ≈ of 0.005. This signals that Nigeria’s development trajectory is positive but too slow to achieve high human development in the near term.

2.	Health improvements are the strongest contributor to HDI growth, shown through a rise in life expectancy by +17 years and a significant decline in infant mortality over time. This shows that improvements in healthcare have delivered the largest and most consistent gains in human development.

3.	However, income growth is weak, and limits development acceleration with GDP per capita at ≈ $1,084 (2024), and the scatter plot shows a positive but moderate relationship with life expectancy. Economic growth is neither strong, stable, nor inclusive enough to accelerate HDI significantly.

4.	Infrastructure expansion is lagging population growth, with electricity access and amenities increasing steadily, but still less compared to population growth, and is unable to meet the requirements of the average Nigerian. Hence, infrastructure development is not keeping pace with demand, reducing its impact on welfare.

5.	The population growth curve is steep and accelerating. At the same time, per capita indicators improve slowly despite absolute gains, suggesting that development gains are being spread across a rapidly expanding population, thereby weakening their impact.

6.	There is a weak correlation between labor force participation and the working-age population. The economy is not effectively absorbing labor, showing structural unemployment or underemployment.

7.	HDI is primarily driven by health, income, and education.
•	Life expectancy (~0.85–0.90) 
•	GNI per capita (~0.75–0.85) 
•	Education (~0.65–0.80) 
These variables are the core levers for accelerating human development.
RECOMMENDATIONS
1.	Nigeria’s current budget allocation for health is NGN2.48 trillion, which is 5.18% of the total budget, the highest in a decade, but still less than the 15% target set by the Abuja Declaration. This limits the substantial impact that can be made in improving health access and availability in most rural and urban areas in Nigeria. The data shows that health has a strong impact on HDI, so it is important to allocate appropriate funding to the 20% that drive 80% of development by providing primary healthcare systems, maternal and child health programs, expanding rural and communal health access, and providing critical health infrastructure like MRI machines in central areas.

2.	Income growth is too weak to drive development, so measures are important to reduce economic inequality and push for inclusive growth. Nigeria is a service-centered economy that hasn’t undergone a proper industrial revolution, which limits the capacity for full or substantial employment. So, it’s important to invest in plants, manufacturing industries through incentives and rebates, agricultural value/supply chain and the digital/creative economy (which is the latest driving force in Nigeria). It is also essential that the government create a robust economic environment that supports SMEs and protects the informal economy, which has been the backbone of the Nigerian economy. The impact would be an increase in GDP per capita and stronger HDI growth through the income channel.

3.	The structural deficiencies in Nigeria have been a huge limitation to growth in several sectors in Nigeria; electricity and digital infrastructure are weak compared to the average African economy, which limits the space for productivity and innovation. In contrast, it is necessary to improve national grid capacity and, equally, renewable energy solutions, especially in rural areas, to boost productivity and living standards.

4.	Education is a core HDI driver, and it is important to increase access to secondary education; change the current curricula also to include technical and vocational training. This would boost higher workforce productivity and long-term HDI growth.

b.	There’s a weak relationship between workforce and employment, so it’s important to align education with labor market needs to promote entrepreneurship and skill-based training. This would reduce unemployment and strengthen economic contributions to HDI.

5.	Adopt Integrated Development Policies because development is uneven across sectors. It’s important to priorities policies and sectors with large multipliers. It is also necessary to pursue growth without weakening the future generation's growth potential. 

6.	I do not believe Nigeria’s problem is purely a population issue because we have one of the largest youthful populations with a median age of 18.1 years, exhibiting demographic dividend, and if huge economic contributions are made in the manufacturing sectors and priorities are set to rise, it would be a huge advantage for driving economic growth. However, population control measures should be put in place to reduce the possibility of turning this advantage into a burden.

In conclusion, Nigeria’s development trajectory is positive but not transformative. Achieving faster and more sustainable progress will require coordinated, high-impact policies that strengthen economic productivity, expand infrastructure, invest in human capital, and address structural challenges.

