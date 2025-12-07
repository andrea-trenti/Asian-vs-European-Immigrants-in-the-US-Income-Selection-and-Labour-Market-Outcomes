# Geography, Cost of Living and Real Income for Asian and European Immigrants in the US

## Abstract

This paper investigates how differences in internal US geography—states and metropolitan areas of residence—interact with cost of living to shape the real incomes of Asian and European immigrants. Using Migration Policy Institute (MPI) regional profiles, ACS-based metropolitan distributions and Census data on median incomes and rents, it shows that Asian immigrants are concentrated in high-income, high-cost metros such as the San Francisco Bay Area, Seattle, New York and Los Angeles, while European immigrants are more evenly spread across the country, including midwestern and southern states with lower wages and lower costs.[1][2][3] Adjusting for local price levels narrows nominal income gaps but does not fully eliminate them, as Asian immigrants still hold more high-wage jobs. A simple model decomposes nominal income into productivity and location components, and illustrative scenarios compare real incomes using state-level price indices. Results highlight that geography amplifies nominal gaps but real-income differences remain driven by occupational and educational factors.

## 1. Introduction

The geography of migration within destination countries matters for both migrants and policymakers. In the US, wage levels and living costs vary dramatically across states and metropolitan areas. A household earning $120,000 in the San Francisco Bay Area may enjoy a standard of living comparable to a $80,000 household in a lower-cost metro.

Asian and European immigrants are not randomly distributed across the US map. Asian immigrants cluster in a small number of gateway metros linked to technology, finance and healthcare, while Europeans are more dispersed. This paper quantifies these patterns and explores their implications for **real**, cost-of-living-adjusted income comparisons.

## 2. Data and stylised facts

### 2.1 Geographic distribution by region of birth

MPI’s Asia and Europe profiles show that:[1][2]

- Around **56%** of Asia-born immigrants live in **five states**: California, New York, Texas, New Jersey and Illinois.  
- Asian immigrants are heavily concentrated in metropolitan areas such as:  
  - **San Jose–Sunnyvale–Santa Clara (Silicon Valley)**;  
  - **San Francisco–Oakland–Berkeley**;  
  - **Los Angeles–Long Beach–Anaheim**;  
  - **New York–Newark–Jersey City**;  
  - **Seattle–Tacoma–Bellevue**.  

- Europe-born immigrants live in California, New York, Florida, New Jersey and several Midwestern states, but with less extreme concentration in a few high-cost metros; notable presence exists in **Chicago**, **Boston**, **Miami**, and various cities in the **Midwest** and **Mountain** regions.[2]

ACS and Census publications confirm that Asian ancestry populations are overrepresented in the West Coast and Northeast, while European ancestry is more evenly distributed.[3]

### 2.2 Regional income and cost-of-living differences

Census and BLS data indicate that:[3][4]

- Median household income in 2023:  
  - **San Jose metro**: >$150,000;  
  - **San Francisco metro**: >$130,000;  
  - **Seattle metro**: >$110,000;  
  - **New York metro**: ~ $90,000–100,000;  
  - Many Midwestern and Southern metros: $60,000–80,000.

- Cost-of-living indices (based on BEA Regional Price Parities and other sources) show that:[4]  
  - Bay Area and coastal California have price levels **20–30%** above the US average.  
  - New York City is about **20%** above the national price level.  
  - Many Midwestern and Southern states have price levels **5–10%** below the national average.

Thus, nominal wages in high-tech coastal hubs are partially offset by higher living costs.

### 2.3 Immigrant incomes by geography

Using ACS and Pew data, we observe that:[3][5]

- Asian-headed households have a median income of **$105,600** nationally, but in some high-tech metros their median income exceeds **$130,000–150,000**.[3]  
- European-headed households show median incomes closer to **$80,000–90,000** in high-cost metros and **$60,000–75,000** in lower-cost regions, depending on occupation and age.  

At national level, as shown in Paper 1, Asia-born immigrant households have a median income of roughly **$105,000–110,000**, versus **$86,000** for Europe-born immigrants.[1][2]

## 3. Framework

To compare **real** income across groups, we define:

$$
y_{g,r}^\text{real} = \frac{y_{g,r}^\text{nominal}}{P_r}
$$

where:

- $y_{g,r}^\text{nominal}$ is the average nominal income of group $g$ in region (state or metro) $r$;  
- $P_r$ is a price index for region $r$ (e.g. Regional Price Parity with US average = 1).

Aggregate real income for group $g$ can be written as:

$$
\bar{y}_g^\text{real} = \sum_r \omega_{g,r} \frac{y_{g,r}^\text{nominal}}{P_r}
$$

with $\omega_{g,r}$ the share of group $g$ living in region $r$.

The Asia–Europe difference in real income becomes:

$$
\bar{y}_A^\text{real} - \bar{y}_E^\text{real} = 
\sum_r \left(\omega_{A,r} \frac{y_{A,r}}{P_r} - \omega_{E,r} \frac{y_{E,r}}{P_r}\right)
$$

In a stylised approach, we cluster regions into:

- **High-cost, high-income** (H): coastal tech and finance hubs;  
- **Medium** (M): average states/metros;  
- **Low-cost, medium-income** (L): lower-cost interior states.

## 4. Scenarios and analysis

### 4.1 Stylised regional shares

Assume the following distributions of households by region type:[1][2]

- **Asians (A)**:  
  - H: 50%  
  - M: 35%  
  - L: 15%

- **Europeans (E)**:  
  - H: 30%  
  - M: 40%  
  - L: 30%

### 4.2 Income and price levels by region type

Let baseline US average income be normalised around the European immigrant median (~$86,000 nominal) for intuitive comparison. We set illustrative values consistent with Census and BLS:

- Region H:  
  - Median nominal income for immigrants:  
    - Asians: $y_{A,H} = 130,000$  
    - Europeans: $y_{E,H} = 100,000$  
  - Price index: $P_H = 1.25$ (25% above national average).  

- Region M:  
  - Asians: $y_{A,M} = 95,000$  
  - Europeans: $y_{E,M} = 80,000$  
  - $P_M = 1.00$.  

- Region L:  
  - Asians: $y_{A,L} = 75,000$  
  - Europeans: $y_{E,L} = 65,000$  
  - $P_L = 0.90$ (10% below national average).

These values reflect higher wages and prices in H, intermediate in M, lower wages but lower prices in L.

### 4.3 Real incomes

Compute real incomes by region:

- Asians:  
  - $y_{A,H}^\text{real} = 130,000 / 1.25 = 104,000$  
  - $y_{A,M}^\text{real} = 95,000 / 1.00 = 95,000$  
  - $y_{A,L}^\text{real} = 75,000 / 0.90 \approx 83,333$

- Europeans:  
  - $y_{E,H}^\text{real} = 100,000 / 1.25 = 80,000$  
  - $y_{E,M}^\text{real} = 80,000 / 1.00 = 80,000$  
  - $y_{E,L}^\text{real} = 65,000 / 0.90 \approx 72,222$

Aggregate:

- Asians:

$$
\bar{y}_A^\text{real} = 0.50 \cdot 104,000 + 0.35 \cdot 95,000 + 0.15 \cdot 83,333
$$

- $0.50 \cdot 104,000 = 52,000$  
- $0.35 \cdot 95,000 = 33,250$  
- $0.15 \cdot 83,333 \approx 12,500$  

Total $\approx 97,750$.

- Europeans:

$$
\bar{y}_E^\text{real} = 0.30 \cdot 80,000 + 0.40 \cdot 80,000 + 0.30 \cdot 72,222
$$

- $0.30 \cdot 80,000 = 24,000$  
- $0.40 \cdot 80,000 = 32,000$  
- $0.30 \cdot 72,222 \approx 21,667$  

Total $\approx 77,667$.

Thus, the real-income difference remains large: about **$20,000$** or **26%**, despite adjusting for cost of living.

### 4.4 Counterfactual: Asians with European geography

Suppose Asians had the same regional distribution as Europeans while retaining their regional nominal incomes:

- Use $y_{A,H}, y_{A,M}, y_{A,L}$ as above, but weights $(0.30, 0.40, 0.30)$.

Compute:

$$
\tilde{y}_A^\text{real} = 0.30 \cdot 104,000 + 0.40 \cdot 95,000 + 0.30 \cdot 83,333
$$

- $0.30 \cdot 104,000 = 31,200$  
- $0.40 \cdot 95,000 = 38,000$  
- $0.30 \cdot 83,333 \approx 25,000$  

Total $\approx 94,200$.

Real-income difference vs Europeans becomes:

$$
94,200 - 77,667 \approx 16,533 \text{ dollars} \ (\approx 21\%)
$$

So equalising geography reduces the real-income gap by a few percentage points but does **not** eliminate it. Most of the difference comes from higher nominal wages in each region, linked to education, occupation and visa selection, rather than from geography alone.

## 5. Risks and caveats

- **Coarse regional grouping**: Real price indices differ within states and within metro areas; using three region types is a simplification.  
- **Household composition**: Differences in household size and composition across groups can affect cost burdens and real living standards; we focus on per-household income.  
- **Endogeneity of location choice**: Higher-skilled migrants may self-select into high-wage, high-cost locations; treating location as exogenous ignores this.  
- **Data gaps**: Precise distributions of Asian vs European immigrants by detailed metro and price index are not available in a single table; we base the stylisation on MPI and Census descriptions.[1][2][3][4]

## 6. Comparison and implications

The comparison shows that:

- Geography amplifies Asia–Europe nominal income differences because Asians are more concentrated in high-wage, high-cost metros.  
- However, adjusting for cost of living still leaves substantial real-income differences, confirming the central role of education and occupational channels.

For **firms**, the implication is that relying heavily on Asian immigrant labour often means operating in expensive labour markets; real labour costs must be assessed net of productivity gains.

For **migrants**, decisions about moving from high-cost hubs to lower-cost regions can significantly change real income even if nominal earnings fall. European migrants located in lower-cost areas may achieve real living standards closer to those of Asians in high-cost hubs than nominal figures suggest.

For **policymakers**, regional policies (e.g. incentives for high-skill jobs in non-coastal regions) can alter the geographic distribution of migrants and potentially spread productivity gains more evenly across the country.

## 7. Conclusion

Asian immigrants’ concentration in high-wage, high-cost metropolitan areas inflates nominal income differences relative to European immigrants, but cost-of-living adjustments reveal that real-income differences remain substantial. Geography is an important amplifying factor, but it does not replace education, occupation and visa selection as primary drivers of the Asia–Europe income gap.

Effective analysis of immigrant outcomes must therefore integrate both labour-market structure and spatial variation in prices. This geographic dimension is especially relevant for policies seeking to redistribute growth and talent beyond traditional gateways.

## References

[1] Migration Policy Institute – *Immigrants from Asia in the United States*, 2025.[0search0]  
[2] Migration Policy Institute – *European Immigrants in the United States*, 2024.[0search9]  
[3] US Census Bureau – ACS metropolitan and state profiles on income and demographic composition.[0search18]  
[4] US Bureau of Economic Analysis – *Regional Price Parities* and related cost-of-living indices.  
[5] Pew Research Center – *Key facts about Asians in the US*, 2025; and related briefs on geographic distribution and income.[0search2][0search10]
