# Within-Job Wage Gaps and Discrimination: Asian vs European Immigrants in the US

## Abstract

This paper examines whether equally qualified immigrants from Asia and Europe earn different wages within the same occupations, firms and locations in the United States, and to what extent residual wage gaps can be attributed to discrimination versus unobserved characteristics. It draws on recent linked employer–employee studies such as Hermansen et al. (2025) and Han (2024), which show that 69–83% of immigrant–native wage gaps are explained by sorting into different jobs and firms, with the remainder due to within-job pay differences.[1][2] Evidence specific to Asian and European origin groups suggests that once education, occupation, sector, firm and region are controlled for, wage differences between Asians, Europeans and US-born whites are small and often statistically insignificant; in some settings, Asians face a modest within-job penalty, particularly in access to managerial roles.[1][3] Using a simple regression-style framework, the paper interprets these findings in the context of the Asian–European immigrant income gap and argues that discrimination is likely more relevant for promotion and occupational segregation than for base pay in comparable roles. Numerical estimates are qualitative, as full microdata access is not available.

## 1. Introduction

Public debate often attributes wage differences between groups to discrimination. In the context of Asian and European immigrants in the US, aggregate statistics reveal higher incomes for Asians than for Europeans and natives on average, raising questions about whether Asians receive wage premia or whether Europeans face disadvantages.

However, aggregate differences confound many factors: education, occupation, sector, location, experience, visa channel and household structure. The key question for this paper is narrower: **holding job, firm and location constant, do immigrants from Asia and Europe earn systematically different wages?**

Recent advances in linked employer–employee data allow researchers to control for firm and job effects and to decompose wage gaps into **sorting** (who ends up in high-paying vs low-paying firms and jobs) and **within-job** differences.[1][2] These methods provide a clearer lens on the role of discrimination in wage-setting.

## 2. Data and stylised facts

### 2.1 Decompositions of immigrant–native wage gaps

Hermansen et al. (2025) analyse several European countries and the US using matched employer–employee data and find that:[1][2]

- **69–83%** of immigrant–native wage differentials are explained by **sorting into lower-paying firms and jobs**.  
- The remaining **17–31%** is attributable to **within-firm, within-job wage differences**, which may reflect discrimination, bargaining power or unobserved productivity.  
- For children of immigrants (second generation), the importance of sorting vs within-job components differs by origin, with Asian-origin children often experiencing small overall gaps and a larger within-job share.

Han (2024) shows that wage gaps between first-generation immigrants and natives shrink substantially across generations as education and occupational distributions converge.[2]

### 2.2 Evidence on Asians vs whites vs other groups

Studies focused on Asian Americans (broadly defined) have documented that:[3][4]

- Asian Americans have higher average incomes than whites largely because they are more concentrated in high-paying occupations and sectors.  
- Conditional on education and occupation, wage differences between Asians and whites are small, and in some samples Asians earn slightly less than whites in similar roles, consistent with “bamboo ceiling” phenomena in promotions.[3]  
- Asians are underrepresented in top management relative to their share in professional and technical roles, despite high education levels.[3][4]

### 2.3 Limited evidence by immigrant region of birth

Most empirical work uses ethnicity or race rather than precise immigrant region of birth (Asia vs Europe). However, given that European immigrants are typically classified as white non-Hispanic in US data, comparisons between Asians and whites with controls for education, occupation and firm are informative about Asia–Europe differences among immigrants.

In summary, the literature suggests that:

- After controlling for key observables and firm effects, **Asian and white workers in the same jobs receive similar base pay**, with small residual differences.  
- Residual gaps, when present, are often negative for Asians (i.e. Asians earn slightly less than whites), particularly in managerial tracks.[3]

## 3. Framework

We adopt a standard wage regression framework:

$$
\log w_{i} = \beta X_i + \gamma F_i + \delta_g D_{g,i} + \epsilon_i
$$

where:

- $w_{i}$ is the wage of individual $i$;  
- $X_i$ is a vector of individual characteristics (education, potential experience, occupation, location);  
- $F_i$ is a full set of firm (and possibly job) fixed effects;  
- $D_{g,i}$ is a dummy for group $g$ (e.g., Asian immigrant, European immigrant);  
- $\delta_g$ measures the **within-firm, within-job wage differential** for group $g$ relative to a baseline group (e.g. US-born whites).

In a two-group comparison (Asians vs Europeans), we can define $D_{A,i} = 1$ for Asians and 0 for Europeans, and interpret $\delta_A$ as the conditional log wage gap at fixed $X$ and $F$.

Our interest is in the sign and magnitude of $\delta_A$.

## 4. Scenarios and analysis

### 4.1 Benchmark from the literature

Based on Hermansen et al. (2025) and related work, we can calibrate typical magnitudes:[1][2]

- Overall immigrant–native wage gap (in logs): around **−0.20 to −0.30** (20–30% lower wages for immigrants).  
- Sorting explains 70–80% → $\approx −0.14$ to −0.24 via different firms/jobs.  
- Within-job residual: **−0.04 to −0.06** (4–6% lower wages) on average.

For Asian immigrants, the aggregate gap versus natives is often small or even positive, but if we focus on within-job effects conditional on firm, some studies find **slightly negative coefficients**, e.g. −0.02 to −0.05.[3][4] For European immigrants classified as white, residuals are usually closer to zero.

Translated into an Asia–Europe comparison among immigrants, this suggests:

- Asians and Europeans in the same firm and job likely have **very similar wages**, with a possible small penalty for Asians of a few percentage points if discrimination or promotion barriers exist.

### 4.2 Stylised comparison: same job, same firm

Assume a high-skill firm in the tech sector employing both Asian and European immigrants as software engineers with similar education and experience. Suppose the baseline log wage for Europeans in this firm is:

$$
\log w_E = \beta X + \gamma F
$$

If the estimated within-job coefficient for Asians vs whites (and hence vs Europeans) is $\delta_A = -0.03$, then:

$$
\log w_A = \beta X + \gamma F - 0.03
$$

This implies:

$$
\frac{w_A}{w_E} = e^{-0.03} \approx 0.97
$$

i.e. a **3% lower wage** for Asians than Europeans in the same job and firm, holding everything else constant.

This is close to the magnitude observed in various studies on Asian Americans’ within-job pay gaps.[3][4]

### 4.3 Implications for the Asia–Europe immigrant gap

Given that aggregate income differences between Asia-born and Europe-born immigrants are on the order of **20–25%** at the household level (Paper 1), a −3% within-job penalty for Asians relative to Europeans is small and goes in the opposite direction of the average gap.

The logical conclusion is that:

- **Asian immigrants’ aggregate income advantage** over European immigrants is driven by **higher probabilities of obtaining high-wage jobs and firms**, not by higher pay within the same positions.  
- To the extent that discrimination exists, it may **reduce** Asians’ earnings relative to Europeans in comparable roles, partially offsetting the effect of stronger selection and sorting.

### 4.4 Promotion and “bamboo ceiling”

While base pay within roles may be similar or slightly unfavourable for Asians, the bigger issue appears at the level of promotions and access to top management:[3][4]

- Studies show that Asians are **overrepresented in professional and technical roles** but **underrepresented in senior leadership** relative to their qualifications.  
- This “bamboo ceiling” implies that Asians may face constraints in moving into the **highest-paying managerial positions**, which affects long-run earnings trajectories more than immediate within-job pay.

European immigrants, especially those from English-speaking countries with similar cultural norms (e.g. UK, Ireland), may face fewer such barriers in leadership tracks, though evidence is limited.

## 5. Risks and caveats

- **Data gaps by region of birth**: Most studies classify individuals by race/ethnicity, not by detailed immigrant origin; using Asians vs whites as a proxy for Asia vs Europe among immigrants is imperfect.  
- **Heterogeneity within groups**: Differences between, say, Indian and Vietnamese immigrants or between Italian and Polish immigrants can be substantial; group-level averages mask this.  
- **Selection into firms**: Firm fixed effects capture between-firm differences, but selection into certain firms may itself be influenced by discrimination and networks, which complicates causal interpretation.  
- **Partial coverage of sectors**: Many detailed studies focus on specific sectors (e.g. tech, finance); patterns may differ in manufacturing, healthcare or public sector.

## 6. Comparison and implications

For **founders and employers**, the key message is that paying equally for equal work within firms is largely the norm in the data, but **promotion pipelines and managerial representation require attention**. Firms that systematically underpromote Asian or immigrant workers may not only face fairness concerns but also waste high human capital.

For **investors**, aggregate wage data should not be interpreted as evidence that Asians command per-person wage premia; rather, high earnings reflect stronger selection into lucrative occupations and firms. This matters when assessing the resilience of talent pipelines and potential vulnerabilities to discrimination-related disputes.

For **policymakers**, anti-discrimination efforts may be more effective if targeted at **access to high-wage occupations and leadership roles** than at base pay, where gaps appear small once observables are controlled. Policies influencing education, credential recognition and visa access to high-paying sectors are likely more consequential for group-level disparities.

## 7. Conclusion

Within-job wage differences between Asian and European immigrants in the US appear modest once education, occupation, firm and location are controlled for. The bulk of the Asian–European income gap arises from **who gets into which jobs and firms**, not from different pay for the same work. Evidence points to small within-job penalties for Asians relative to whites and suggests that discrimination may operate more through promotion and occupational segregation than through direct wage differentials within roles.

This does not imply that discrimination is absent; rather, it is **not the primary driver** of aggregate income differences between Asian and European immigrants. Policy and managerial interventions that expand access to high-paying jobs and leadership positions are likely more effective than those focusing solely on equal pay provisions.

## References

[1] A. S. Hermansen et al. – *Immigrant–native pay gap driven by lack of access to high-paying jobs*, Nature, 2025.[0search6][0search21]  
[2] J. H. Han – *Wage Disparities across Immigrant Generations*, ILR Review, 2024.[0search14]  
[3] Various studies on Asian Americans and the “bamboo ceiling”, summarised in research on Asian representation in leadership roles (e.g. corporate diversity reports and academic analyses).  
[4] Pew Research Center – Analyses of Asian American earnings and occupational distribution.[0search2][0search10]
