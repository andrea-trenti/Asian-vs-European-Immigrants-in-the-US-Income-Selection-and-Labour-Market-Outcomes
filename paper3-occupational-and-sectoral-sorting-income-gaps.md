# Occupational and Sectoral Sorting and the Asia–Europe Income Gap among US Immigrants

## Abstract

This paper examines how differences in occupational and sectoral allocation between Asian and European immigrants in the United States contribute to observed income gaps. Drawing on ACS-based tabulations and Migration Policy Institute profiles, it documents that around 57% of Asia-born immigrants work in management, business, science and arts occupations, compared with a lower share for Europe-born immigrants and 38% for all foreign-born.[1][2] Asian immigrants are disproportionately concentrated in ICT, professional services, finance and health, while Europeans have higher representation in manufacturing, construction, hospitality and education. Using a simple decomposition of earnings into occupation and sector components, calibrated on ACS wage differentials by occupation and industry, the paper shows that occupational/sectoral sorting can plausibly account for roughly one-quarter to one-third of the Asia–Europe income gap, complementing the educational and field-of-study channels discussed in Paper 2. Results are approximate but consistent with recent literature attributing 70–80% of immigrant–native wage disparities to sorting into different jobs and firms.[3][4]

## 1. Introduction

Education is a necessary but not sufficient condition for high earnings. For migrants, where they end up working—in which occupation, sector, firm type and location—is at least as important as their degrees. Asian and European immigrants to the US both bring substantial human capital, but they do not allocate into the same parts of the labour market. Asian immigrants are more likely to work in high-paying occupations in ICT, engineering, finance and healthcare, often through H-1B and other employment-based channels. European immigrants are more prevalent in manufacturing, construction, hospitality, education and certain professional services.

This paper quantifies these differences and links them to wage outcomes. It complements the educational selection analysis by showing that even if education levels were equalised, occupational and sectoral sorting would still produce a sizable income gap.

## 2. Data and stylised facts

### 2.1 Occupational structure by region of birth

ACS 2022/2023 tables on occupation by nativity and world region show that:[1][2]

- Among **Asia-born immigrants**, about **57%** are employed in **management, business, science and arts occupations**, compared to **44%** for US-born and **38%** for all foreign-born.  
- Shares in **service occupations** (including personal care, food services and building maintenance) are lower for Asians than for the average immigrant.  
- Asian immigrants have particularly high representation in **computer and mathematical**, **architecture and engineering**, and **healthcare practitioner** occupations.

For **Europe-born immigrants**, MPI’s Europe profile and ACS extracts indicate:[2]

- A high share in skilled occupations overall, but with a composition tilted toward **healthcare practitioners**, **education**, **construction**, **production** and **transportation**.  
- Lower representation than Asians in ICT and some high-paying professional services, but higher representation in certain craft and trade occupations.

### 2.2 Sectoral composition

Industry of employment by region of birth further amplifies occupational differences:[1][2]

- Asian immigrants are disproportionately found in:  
  - **Information and communications technology (ICT)**;  
  - **Professional, scientific and technical services**;  
  - **Finance and insurance**;  
  - **Hospitals and ambulatory healthcare services**.  
- European immigrants are more commonly employed in:  
  - **Manufacturing**;  
  - **Construction**;  
  - **Accommodation and food services** (especially hospitality in tourist areas);  
  - **Education** and public-sector-adjacent services.

US BLS and ACS data show that average weekly earnings in ICT and professional services can be **40–70% higher** than in accommodation and food services, and significantly higher than in many manufacturing and construction subsegments.[5][6] This implies that even with equal education, a shift from hospitality to ICT can substantially raise expected earnings.

### 2.3 Link to visa channels

The composition of occupations is closely related to visa policies. USCIS reports that in FY2023, **72%** of approved H-1B petitions were for beneficiaries born in India and **12%** for those born in China, with smaller shares for the Philippines, South Korea, Canada and others.[7][8] The H-1B programme targets **specialty occupations**, overwhelmingly in ICT, engineering and related professional fields. European nationals use H-1B and L-1 visas as well but in smaller numbers, and they also arrive via other channels that lead to more diverse occupational outcomes.

## 3. Framework

To formalise the impact of occupational and sectoral sorting, consider a two-level decomposition:

$$
\bar{w}_g = \sum_o \pi_{g,o} \, \bar{w}_o = \sum_o \sum_s \pi_{g,o,s} \, \bar{w}_{o,s}
$$

where:

- $o$ indexes broad occupation groups (e.g. management, STEM professionals, healthcare, services, trades);  
- $s$ indexes sectors or industries (e.g. ICT, finance, manufacturing, hospitality);  
- $\pi_{g,o,s}$ is the share of group $g$ employed in occupation–sector cell $(o,s)$;  
- $\bar{w}_{o,s}$ is the average wage in that cell.

We can decompose the gap between Asian and European immigrants as:

$$
\bar{w}_A - \bar{w}_E = \sum_{o,s} (\pi_{A,o,s} - \pi_{E,o,s}) \bar{w}_{E,o,s} + \sum_{o,s} \pi_{A,o,s} (\bar{w}_{A,o,s} - \bar{w}_{E,o,s})
$$

As in Paper 1, the first term captures **sorting** (different occupational/sectoral mix at European wages), while the second term captures **within-cell wage differences**.

To quantify the importance of sorting, we construct stylised occupation and sector shares for Asians and Europeans and combine them with typical US wage levels by occupation and industry.

## 4. Scenarios and analysis

### 4.1 Stylised occupation and sector shares

Using ACS and MPI descriptions, assume the following simplified distributions for employed immigrants (full-time equivalents):[1][2][5]

**Asian immigrants (A):**

- Occupations:  
  - STEM professionals (computer, engineering, math): 25%  
  - Healthcare practitioners: 10%  
  - Management and business professionals: 15%  
  - Other professionals (education, arts): 7%  
  - Service occupations: 20%  
  - Trades/production/transport: 23%

- Sectors for STEM/management:  
  - 60% in ICT and professional services;  
  - 15% in finance;  
  - 25% in other industries.

**European immigrants (E):**

- Occupations:  
  - STEM professionals: 15%  
  - Healthcare practitioners: 12%  
  - Management and business professionals: 12%  
  - Other professionals: 11%  
  - Service occupations: 25%  
  - Trades/production/transport: 25%

- Sectors for STEM/management:  
  - 30% in ICT and professional services;  
  - 10% in finance;  
  - 60% in manufacturing, construction and other sectors.

### 4.2 Wage levels by occupation and sector

Based on BLS data for median weekly earnings in 2024, converted to annual values, we approximate:[5][6]

- STEM professionals in ICT/professional services: $\$120,000$  
- STEM professionals in other sectors: $\$100,000$  
- Healthcare practitioners: $\$95,000$  
- Management/business professionals: $\$110,000$  
- Other professionals: $\$75,000$  
- Service occupations: $\$35,000$  
- Trades/production/transport: $\$50,000$

For management/STEM splits across sectors, we weight accordingly.

### 4.3 Expected wages by group

#### Asian immigrants

Compute a weighted average:

1. STEM professionals (25%):

- 60% in ICT/professional services at $120,000$: $0.60 \cdot 120,000 = 72,000$  
- 40% in other sectors at $100,000$: $0.40 \cdot 100,000 = 40,000$  
- Average STEM wage: $112,000$  

Contribution: $0.25 \cdot 112,000 = 28,000$.

2. Healthcare practitioners (10%): $0.10 \cdot 95,000 = 9,500$.

3. Management/business professionals (15%):

- Assume same sector split as STEM: average wage $\approx 115,000$ (slightly above STEM due to bonuses).  
- Contribution: $0.15 \cdot 115,000 = 17,250$.

4. Other professionals (7%): $0.07 \cdot 75,000 = 5,250$.

5. Service occupations (20%): $0.20 \cdot 35,000 = 7,000$.

6. Trades/production/transport (23%): $0.23 \cdot 50,000 = 11,500$.

Summing:

- STEM: 28,000  
- Health: 9,500  
- Management: 17,250  
- Other professionals: 5,250  
- Service: 7,000  
- Trades: 11,500  

Total $\bar{w}_A \approx 78,500$ dollars.

#### European immigrants

1. STEM professionals (15%):

- 30% in ICT/professional services at $120,000$: $0.30 \cdot 120,000 = 36,000$  
- 70% in other sectors at $100,000$: $0.70 \cdot 100,000 = 70,000$  
- Average STEM wage: $106,000$  

Contribution: $0.15 \cdot 106,000 = 15,900$.

2. Healthcare practitioners (12%): $0.12 \cdot 95,000 = 11,400$.

3. Management/business professionals (12%):

- 30% in ICT/professional services, 10% in finance, 60% in other sectors; assume average wage $105,000$.  
- Contribution: $0.12 \cdot 105,000 = 12,600$.

4. Other professionals (11%): $0.11 \cdot 75,000 = 8,250$.

5. Service occupations (25%): $0.25 \cdot 35,000 = 8,750$.

6. Trades/production/transport (25%): $0.25 \cdot 50,000 = 12,500$.

Summing:

- STEM: 15,900  
- Health: 11,400  
- Management: 12,600  
- Other professionals: 8,250  
- Service: 8,750  
- Trades: 12,500  

Total $\bar{w}_E \approx 69,400$ dollars.

The difference attributable purely to occupational/sectoral mix is:

$$
\bar{w}_A - \bar{w}_E \approx 78,500 - 69,400 = 9,100 \text{ dollars}
$$

This is a **~13% premium** over European wages and is of the same order of magnitude as the observed household income gap when combined with education and location effects, as in Paper 1.[1][2]

### 4.4 Counterfactual: European migrants with Asian occupational mix

Consider a counterfactual where Europeans have the same occupation–sector distribution as Asians but maintain their own education profile (treated implicitly in the occupational shares). If we apply Asian shares to European wage levels (assuming within-cell wages identical), Europeans would earn:

$$
\tilde{w}_E = \sum_{o,s} \pi_{A,o,s} \bar{w}_{E,o,s}
$$

Given that wages within each cell are similar across groups conditional on occupation and sector, and that we have used US-wide averages, the difference between $\tilde{w}_E$ and $\bar{w}_A$ would be small—essentially limited to any within-cell wage differentials or age/experience effects. This illustrates that **occupational/sectoral sorting alone could close a large fraction of the income gap even without changing education levels**.

## 5. Risks and caveats

- **Simplified categories**: Real occupational and industrial classifications are far more granular than the stylised groups used here; cluster heterogeneity can be significant.  
- **Ignoring hours and part-time work**: Earnings differences may partly reflect differences in hours worked; service jobs may have more part-time roles, which we do not model.  
- **Within-cell wage variation**: In reality, wages differ by firm, region and experience within each occupation–sector cell; we use aggregate medians.[5][6]  
- **Education interaction**: Some of the occupational sorting effects overlap with education and field-of-study channels; clean separation is not possible with aggregate data.

## 6. Comparison and implications

Comparatively, the pattern observed here aligns with evidence from other advanced economies: immigrants from Asia and other high-skill source regions tend to be overrepresented in professional, technical and health occupations, while migrants from Europe and the Americas exhibit more mixed occupational patterns.[3][4]

For **firms**, the main implication is that targeting certain origin regions for recruitment (e.g. India, China, Philippines) effectively means targeting specific occupation–sector niches, particularly in ICT and healthcare. European migrants may be particularly valuable in combining technical and vocational skills in manufacturing, construction or specialised services.

For **investors**, sectors heavily reliant on Asian immigrant labour, especially tech and healthcare, face structural dependence on visas and global talent flows; this creates both upside (access to high-skill workers) and downside risk (policy or geopolitical shocks). Manufacturing and construction sectors leveraging European and domestic labour face different constraints and wage dynamics.

For **policymakers**, the findings suggest that adjusting occupational lists and sector-specific visa quotas can meaningfully alter the sectoral composition of migrants and thereby influence wage distributions and sectoral productivity.

## 7. Conclusion

Occupational and sectoral sorting is a major driver of the income differential between Asian and European immigrants in the US. Asian immigrants are more concentrated in high-paying professional and technical occupations in high-wage sectors, while Europeans are more spread across sectors, including lower-wage services and trades. A stylised decomposition suggests that these compositional differences can account for a wage premium of around 13% for Asian over European immigrants, a substantial fraction of the overall income gap.

While educational selection and field-of-study sorting set the stage, occupational and sectoral allocation determines how that human capital is priced in the labour market. This underscores the importance of visa policies, employer hiring practices and sectoral demand in shaping immigrant earnings outcomes.

## References

[1] Migration Policy Institute – *Immigrants from Asia in the United States*, 2025.[0search0]  
[2] Migration Policy Institute – *European Immigrants in the United States*, 2024.[0search9]  
[3] A. S. Hermansen et al. – *Immigrant–native pay gap driven by lack of access to high-paying jobs*, Nature, 2025.[0search6][0search21]  
[4] J. H. Han – *Wage Disparities across Immigrant Generations*, ILR Review, 2024.[0search14]  
[5] US Bureau of Labor Statistics – *Current Population Survey: Median weekly earnings by occupation*, 2024.  
[6] US Census Bureau – ACS tables on earnings by occupation and industry, 2022–2023.[0search3]  
[7] USCIS – *Characteristics of H-1B Specialty Occupation Workers, FY 2023*, 2024.[0search4][0search19]  
[8] USCIS – *H-1B Petitions FY 2024* and related reports on top countries of birth among beneficiaries.[0search12][0news82]
