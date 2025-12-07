# Visa Channels as Wage Filters: H-1B, Study–Work Pipelines and Employment-Based Green Cards

## Abstract

This paper analyses how US visa channels act as implicit wage filters and shape the composition and earnings of Asian and European immigrants. It combines USCIS reports on H-1B and employment-based immigration with Migration Policy Institute (MPI) data on legal status and Pew evidence on education and income by origin. In FY2023, 72% of approved H-1B petitions were for India-born workers and 12% for China-born workers, with remaining top countries including the Philippines and South Korea; no European country reaches double-digit shares.[1][2] Employment-based green cards also disproportionately accrue to Asia-born applicants. Because these programmes require a US job offer, minimum wage levels and specific qualifications, they generate strong positive selection on education, field-of-study and wage potential. The paper constructs a simple model linking visa-type composition to expected wages and shows that differential use of high-skill channels can plausibly explain a significant portion of the Asian–European immigrant income gap, especially at the upper tail. Quantitative results are illustrative but grounded in official statistics.

## 1. Introduction

US immigration policy is a complex mix of family-based, employment-based, humanitarian and diversity channels. For high-skilled workers, the dominant routes are:

- **Temporary work visas** (notably H-1B and L-1);  
- **Study-and-work pipelines** (F-1 → OPT → H-1B → employment-based green card);  
- **Employment-based (EB) immigrant visas** (EB-1, EB-2, EB-3).

These channels are tightly linked to labour-market conditions: employers sponsor workers where they expect high productivity and can meet wage and compliance requirements.

Asian immigrants, particularly from India and China, make far more intensive use of these high-skill channels than European immigrants.[1][2] This concentrates them in high-paying jobs and leads to income distributions markedly different from those of migrants entering mainly via family or diversity programmes.

This paper formalises the selection mechanisms embedded in visa rules and quantifies their potential impact on earnings by origin region.

## 2. Data and stylised facts

### 2.1 H-1B petitions by country of birth

USCIS’s FY2023 *Annual Report on H-1B Petitions* shows that:[1][2]

- A total of about **409,000** H-1B petitions (initial and continuing) were approved.  
- **72%** of beneficiaries were born in **India**.  
- **12%** were born in **China**.  
- The remaining top 10 countries include the Philippines, South Korea, Canada and others, each with shares of **1–2%**.  

In FY2024, similar patterns persisted: Indian-born workers accounted for about **71%** of beneficiaries, with Chinese-born around **11–12%**.[2][0news82]

H-1B occupations are overwhelmingly in **computer-related fields, engineering, mathematics, and healthcare**, with median offered salaries well above national averages.

### 2.2 Employment-based green cards

DHS and MPI data indicate that in recent years, approximately **140,000** employment-based immigrant visas (green cards) are available annually (subject to per-country limits and spillovers).[3][4] Asia-born applicants receive a large majority of EB visas, especially in EB-2 and EB-3 categories (advanced degrees and skilled workers), while Europeans receive a smaller share relative to their population.

Although precise shares by country are complex due to per-country caps and backlogs, MPI estimates and DHS statistics suggest that:

- India, China and the Philippines are consistently among the top recipients of EB visas;  
- Europe’s share is significantly lower, reflecting both fewer employment-based applications and greater reliance on family-based and diversity categories.[3][4]

### 2.3 Legal status composition by region of birth

MPI’s regional profiles show that:[3][5]

- A higher share of **Asia-born immigrants** are **naturalised US citizens** compared to the overall foreign-born population, reflecting longer residence and high rates of adjustment from temporary work or student status to permanent residence.  
- A significant fraction of recent Asia-born arrivals entered on student visas or H-1B, while family-based entry remains important.  
- For **Europe-born immigrants**, legal status composition is more mixed, with a notable presence of family-based immigrants, refugees (e.g. Ukrainians in recent years) and diversity-lottery recipients.

Because employment-based and high-skill temporary visas require employer sponsorship and minimum wage levels, groups that rely more on these channels will be more heavily selected on earnings potential.

## 3. Framework

Consider three broad visa categories relevant for adult economic immigrants:

1. **High-skill work visas and EB categories** ($V_H$): H-1B, L-1, O-1, EB-1, EB-2, EB-3.  
2. **Study-and-work pipelines** ($V_S$): F-1 → OPT → H-1B/EB.  
3. **Non-skill-filtering channels** ($V_N$): family-based, diversity lottery, humanitarian (apart from certain occupational preferences).

Let group $g$ have shares $(\alpha_{g,H}, \alpha_{g,S}, \alpha_{g,N})$ across these channels. Expected wages for group $g$ can be written as:

$$
\bar{w}_g = \alpha_{g,H} \mu_H + \alpha_{g,S} \mu_S + \alpha_{g,N} \mu_N
$$

where:

- $\mu_H$ is the expected wage for workers entering via high-skill work/EB channels;  
- $\mu_S$ for those entering via study pipelines;  
- $\mu_N$ for those entering via non-skill-filtering channels.

We assume $\mu_H > \mu_S > \mu_N$ due to selection on job offer, wage thresholds and education.

For simplicity, we treat origin-region wage differences within each channel as second-order; more detailed modelling would nest the education and occupational structure inside each $\mu_\cdot$.

## 4. Scenarios and analysis

### 4.1 Channel shares by region (stylised)

Based on USCIS, MPI and Pew evidence, we adopt stylised shares for recent cohorts of working-age immigrants:[1][3][5]

- **Asia-born immigrants**:  
  - High-skill work/EB ($\alpha_{A,H}$): 0.40  
  - Study pipelines ($\alpha_{A,S}$): 0.25  
  - Non-filtering channels ($\alpha_{A,N}$): 0.35  

- **Europe-born immigrants**:  
  - High-skill work/EB ($\alpha_{E,H}$): 0.20  
  - Study pipelines ($\alpha_{E,S}$): 0.15  
  - Non-filtering channels ($\alpha_{E,N}$): 0.65  

These numbers are not exact but reflect that Asian migrants rely more on H-1B and F-1/OPT while Europeans have a larger family/diversity component.[1][3][5]

### 4.2 Wage levels by channel

Using ACS and USCIS wage data, we approximate:[1][6][7]

- $\mu_H \approx \$110,000$ (median salary for H-1B and EB-2/EB-3 workers).  
- $\mu_S \approx \$80,000$ (US-educated graduates transitioning from F-1/OPT to the labour market, including some non-H-1B roles).  
- $\mu_N \approx \$60,000$ (family-based and other entrants across a wider distribution of occupations).

These are conservative estimates; some H-1B workers earn much more, especially in large tech firms.

### 4.3 Expected wages by region

Calculate:

- Asians:

$$
\bar{w}_A = 0.40 \cdot 110{,}000 + 0.25 \cdot 80{,}000 + 0.35 \cdot 60{,}000
$$

- $0.40 \cdot 110,000 = 44,000$  
- $0.25 \cdot 80,000 = 20,000$  
- $0.35 \cdot 60,000 = 21,000$  

Total: $\bar{w}_A = 85,000$.

- Europeans:

$$
\bar{w}_E = 0.20 \cdot 110{,}000 + 0.15 \cdot 80{,}000 + 0.65 \cdot 60{,}000
$$

- $0.20 \cdot 110,000 = 22,000$  
- $0.15 \cdot 80,000 = 12,000$  
- $0.65 \cdot 60,000 = 39,000$  

Total: $\bar{w}_E = 73,000$.

The difference of **$12,000$**, or about **16%**, is attributable purely to the different portfolio of visa channels.

### 4.4 Counterfactual: European migrants with Asian visa mix

If European migrants had the same visa-channel composition as Asians, their expected wage would be:

$$
\tilde{w}_E = 0.40 \cdot 110{,}000 + 0.25 \cdot 80{,}000 + 0.35 \cdot 60{,}000 = 85,000
$$

i.e. equal to $\bar{w}_A$ under our assumptions. This indicates that **visa-channel composition alone could potentially close most of the wage gap**, if educational attainment and occupational choices conditional on channel were similar.

In reality, channel composition and education/occupation are jointly determined: those with higher education and higher expected wages are more likely to obtain H-1B or EB visas, which further boosts their earnings.

## 5. Risks and caveats

- **Simplistic channel partition**: In practice, individuals may change channels over time (e.g. from student to H-1B to EB-2 to naturalised citizen). Our static partition is a simplification.  
- **Within-channel heterogeneity**: Not all H-1B or EB workers earn high salaries; wage distributions within channels are wide.  
- **Data limitations by region**: USCIS reports H-1B and EB statistics by country of birth, but linking these precisely to ACS wage data at the person level requires microdata and careful matching.[1][2][4]  
- **Policy changes**: Visa rules, caps and country-specific backlogs evolve over time, affecting both selection and outcomes; our analysis is cross-sectional.

## 6. Comparison and implications

The US system differs from pure points-based systems (like Canada’s Express Entry), but in practice the combination of H-1B, F-1/OPT and EB channels functions as a **de facto points system** for many Asian migrants: strong emphasis on STEM degrees, employer sponsorship and wage thresholds.[1][6][7]

For **firms**, this means that high-skill visa channels are effectively pipelines for high-wage human capital from a relatively narrow set of countries (notably India and China). Disruptions to these channels—through policy changes, backlog management or geopolitical tensions—would disproportionately affect sectors relying on Asian immigrant labour.

For **European migrants**, the heavier reliance on family-based and diversity visas implies a more heterogeneous skill and wage profile. Highly skilled Europeans still use H-1B and EB channels, but in aggregate their share is lower, which helps explain aggregate income differences despite many individual Europeans performing well.

For **policymakers**, adjusting channel composition (e.g. raising employment-based quotas, redesigning H-1B allocation, or introducing points-like mechanisms) would reshape not only the number but also the wage distribution of future immigrants.

## 7. Conclusion

Visa channels are powerful wage filters. High-skill work visas and employment-based green cards, heavily used by Asian migrants, selectively admit individuals with high education and wage potential. European migrants, with a greater reliance on family-based and diversity entries, exhibit a more mixed distribution of skills and earnings. A simple three-channel model suggests that differences in visa-channel composition alone can produce a wage premium of around 16% for Asian over European immigrants.

These findings do not negate the importance of education, occupation and geography, but they emphasise that **policy design in the migration regime is itself a key driver of observed income differentials**. Understanding and adjusting this lever is central for any strategy aimed at steering the composition and economic impact of immigration.

## References

[1] USCIS – *Characteristics of H-1B Specialty Occupation Workers, FY 2023*, 2024.[0search4]  
[2] USCIS – *FY 2023–2024 H-1B Petitions* and related reports on top countries of birth.[0search19][0search12][0news82]  
[3] Migration Policy Institute – *Frequently Requested Statistics on Immigrants and Immigration in the United States*, 2025.[0search1]  
[4] US Department of Homeland Security – *Yearbook of Immigration Statistics*, latest editions, tables on employment-based legal permanent residents.  
[5] Migration Policy Institute – Regional profiles for Asia-born and Europe-born immigrants showing legal status composition.[0search0][0search9]  
[6] US Census Bureau – ACS-based earnings distributions by industry and occupation.  
[7] Pew Research Center – Analyses of Indian and Chinese Americans’ education and income, highlighting high shares of H-1B and STEM occupations.[0search2][0news81]  
[8] OECD – *International Migration Outlook* chapters on high-skilled migration and visa regimes.
