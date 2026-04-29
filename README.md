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


## KEY INSIGHTS

<img width="975" height="626" alt="image" src="https://github.com/user-attachments/assets/b2579121-685a-4955-a0f2-fa028ec1844d" />

1. HDI has improved, but progress is slow and incremental; it has increased from 0.38 (1990) → 0.56 (2023), a total change of +0.18 over ~33 years and an annual average growth ≈ of 0.005. This signals that Nigeria’s development trajectory is positive but too slow to achieve high human development in the near term.
   
2. Health improvements are the strongest contributor to HDI growth, shown through a rise in life expectancy by +17 years and a significant decline in infant mortality over time. This shows that improvements in healthcare have delivered the largest and most consistent gains in human development.

3. However, income growth is weak, and limits development acceleration with GDP per capita at ≈ $1,084 (2024), and the scatter plot shows a positive but moderate relationship with life expectancy. Economic growth is neither strong, stable, nor inclusive enough to accelerate HDI significantly.

4. Infrastructure expansion is lagging population growth, with electricity access and amenities increasing steadily, but still less compared to population growth, and is unable to meet the requirements of the average Nigerian. Hence, infrastructure development is not keeping pace with demand, reducing its impact on welfare.

5. The population growth curve is steep and accelerating. At the same time, per capita indicators improve slowly despite absolute gains, suggesting that development gains are being spread across a rapidly expanding population, thereby weakening their impact.

6. There is a weak correlation between labor force participation and the working-age population. The economy is not effectively absorbing labor, showing structural unemployment or underemployment.

7. HDI is primarily driven by health, income, and education.
•	Life expectancy (~0.85–0.90) 
•	GNI per capita (~0.75–0.85) 
•	Education (~0.65–0.80) 
These variables are the core levers for accelerating human development.

## RECOMMENDATIONS
1. Nigeria’s current budget allocation for health stands at NGN 2.48 trillion, representing 5.18% of the total budget. Although this is the highest level in a decade, it remains significantly below the 15% target set by the Abuja Declaration. This shortfall constrains the country’s ability to meaningfully improve healthcare access and quality across both rural and urban areas. Given the strong relationship between health outcomes and the Human Development Index, prioritizing high-impact interventions is essential. These include strengthening primary healthcare systems, expanding maternal and child health programs, improving rural and community health access, and investing in critical infrastructure such as MRI facilities in key regional cerntres.

2. Income growth in Nigeria remains insufficient to drive substantial development, making it necessary to adopt policies that reduce inequality and promote inclusive growth. As a service-driven economy that has not undergone full industrialization, Nigeria faces structural constraints in achieving large-scale employment. To address this, investments should be directed toward manufacturing through targeted incentives, strengthening agricultural value chains, and expanding the digital and creative economy, which is increasingly emerging as a key growth driver. Additionally, the government must create an enabling environment for SMEs while safeguarding the informal sector, which remains the backbone of economic activity. These measures would increase GDP per capita and enhance HDI performance through the income dimension.

3.  Structural deficiencies continue to limit growth across multiple sectors. In particular, weak electricity supply and underdeveloped digital infrastructure hinder productivity and innovation compared to peer economies. Addressing this requires significant improvements in national grid capacity alongside the expansion of renewable energy solutions, especially in underserved rural areas. Enhancing infrastructure in these areas would directly improve productivity, business efficiency, and overall living standards.
   
4. Education remains a core driver of HDI and requires both expanded access and improved quality. Increasing enrollment in secondary education is critical, alongside reforming curricula to incorporate technical and vocational training. This would enhance workforce productivity and support long-term human capital development. There is currently a weak alignment between education outcomes and labor market needs. Bridging this gap through skill-based training and entrepreneurship-focused education are essential to reducing unemployment and strengthening the workforce’s contribution to economic growth and HDI.

5. Nigeria should adopt integrated development policies to address uneven progress across sectors. Prioritizing sectors with high multiplier effects will ensure more efficient resource allocation and greater developmental impact. At the same time, growth strategies must remain sustainable, ensuring that current progress does not compromise the welfare and opportunities of future generations. 

6. Nigeria’s development challenges are not solely driven by population growth. With a median age of 18.1 years, the country possesses a significant demographic advantage. If effectively harnessed through strategic investments in sectors such as manufacturing and human capital development, this youthful population can drive rapid economic expansion. However, appropriate population management policies are still necessary to prevent this potential advantage from becoming a long-term burden.
   
In conclusion, Nigeria’s development trajectory is positive but not transformative. Achieving faster and more sustainable progress will require coordinated, high-impact policies that strengthen economic productivity, expand infrastructure, invest in human capital, and address structural challenges.

