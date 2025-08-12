**Paper Research Questions Review**

This file takes the paper itself, a_summary.md and 2_filled.md (for research questions) to conduct an analysis driven by the user's research questions.

Where a_summary.md ascertains the nature of the paper and does not use 1_scope.md or 2_filled.md in any way, thus is more broad and blue-sky-thinking in the information it obtains from the paper. And where b_scope.md takes the paper itself, a_summary.md and 1_scope.md (for scope points) to conduct an analysis driven by the user's scope points.

**----------------- TEMPLATE BELOW -----------------**

# Source 1 
# ----------------- AT A GLANCE ------------------

## "The Future of Employment: How Susceptible Are Jobs to Computerisation?" (Frey & Osborne, 2013)
- Source: Oxford Martin School
- Focus: Job automation vulnerability analysis across 702 occupations
- [findings]: 47% of US jobs are at high risk of automation; Used machine learning (Gaussian Process classifier) to analyze 702 occupations; Found strong negative correlation between wages/education and automation risk 
- [conclusion]: The paper's findings suggest that low-skill workers will need to acquire creative and social skills to remain competitive, which will exacerbate inequality and automation effects.

## Scope
- (Point 2) [2_automatable/]): Analyzes 702 occupations for automation susceptibility, identifying specific job categories at risk
- (Point 3) [3_effects/]: Focuses on employment displacement effects, finding 47% of US jobs at high risk
- (Point 4) [4_experiments/]: Uses task-based analysis methodology to evaluate automation potential across occupations
- (Point 5) [5_conclusions/]: Rapid automation is accelerating beyond manufacturing into services, with 47% of US jobs at risk, requiring major workforce adaptation and likely exacerbating inequality

## Research Questions:
- The paper is strongest on technical methodology and employment analysis but weaker on policy implications and broader social impacts.
- Strongly addressed (4/10):
    - [1_measurement] 
        - Provides methodology for measuring automation risk
    - [2_sources_and_metrics] 
        - Develops novel quantitative framework using occupational data and machine learning
    - [3_automatable] 
        - Directly addresses which jobs are vulnerable to automation and what skills remain valuable
    - [6_inequality] 
        - Analyzes how automation disproportionately affects low-wage jobs and exacerbates inequality
- Partially addressed (2/10):
    - [8_demographics] 
        - Implicitly touches on demographic differences through occupation analysis but only education not age/location
    - [4_big_tech] - mentioned but not analyzed
- Not addressed (4/10):
    - [5_SME_bureacrats] - Small business/gig workers
    - [7_job_quality] - Job quality
    - [9_mitigation] - Mitigation policies
    - [10_societal] - Environmental/social costs

## Limitations Acknowledged:
- Focuses on technological capability, not actual adoption
- Doesn't account for wage levels, capital prices, or labor shortages
- Regulatory and political factors not considered
- No timeline predictions for engineering breakthroughs

# -------------------- IN DETAIL ------------------

### A. Methodological Questions

**[1_measurement]** How can we measure the true economic impact of automation beyond simple job displacement? Directly addressed and a key contribution.

> "To our knowledge, no study has yet quantified what recent technological progress is likely to mean for the future of employment. The present study intends to bridge this gap in the literature." (p. 3)

> "We make no attempt to estimate how many jobs will actually be automated. The actual extent and pace of computerisation will depend on several additional factors which were left unaccounted for." (p. 41)

Methodology innovation:

> "We implement a novel methodology to estimate the probability of computerisation for 702 detailed occupations, using a Gaussian process classifier." (p. 1)

**Task-based Analysis Approach:**
The study identified engineering bottlenecks that prevent automation through systematic analysis:
- **Perception and manipulation tasks**: Robots struggle with unstructured environments
- **Creative intelligence tasks**: Difficult to encode creative values in programs
- **Social intelligence tasks**: Challenges in real-time emotion recognition

**[2_sources_and_metrics]** What data sources and metrics are most reliable for tracking automation's effects on inequality? Directly addressed.

> "Accordingly, ONET has the advantage of providing more recent information on occupational work activities." (p. 4)

> "We rely on the 2010 version of the DOT successor ONET – an online service developed for the US Department of Labor." (p. 4)

**Machine Learning Methodology:**
- Used ONET data (9 key variables) to train a classifier on 70 hand-labeled occupations
- Applied Gaussian Process classifier to predict automation probability for all 702 occupations
- Combined with employment data from Bureau of Labor Statistics
- Integrated wage and educational attainment data for comprehensive analysis

Metrics used:
- ONET occupational variables (9 key variables)
- Employment data from Bureau of Labor Statistics
- Wage and educational attainment data
- Probability scores for automation risk

### B. Economic Questions

**[3_automatable]** Which jobs are most vulnerable to automation in the next 5 years, and what skills will remain valuable? Directly addressed - this is the paper's primary focus:

> "According to our estimates around 47 percent of total US employment is in the high risk category." (p. 43)

> "Our model predicts that most workers in transportation and logistics occupations, together with the bulk of office and administrative support workers, and labour in production occupations, are at risk." (p. 43)

> "More surprisingly, we find that a substantial share of employment in service occupations, where most US job growth has occurred over the past decades (Autor and Dorn, 2013), are highly susceptible to computerisation." (p. 44)
Protected skills identified:

> "For workers to win the race, however, they will have to acquire creative and social skills." (p. 44)

> "Our findings thus imply that as technology races ahead, low-skill workers will reallocate to tasks that are non-susceptible to computerisation – i.e., tasks requiring creative and social intelligence." (p. 44)

**[4_big_tech]** What role do large tech companies and key automation players have in shaping the economic landscape and competition? Mentioned but not deeply analyzed.

> "The autonomous driverless cars, developed by Google, provide one example of how manual tasks in transport and logistics may soon be automated." (p. 3)

> "In the section "In Domain After Domain, Computers Race Ahead", they emphasise how fast moving these developments have been." (p. 3)

**[5_SME_bureacrats]** How are small-to-medium enterprises and bureacratic institutions like governments affected, can they adapt to the wave of automation? Not addressed - The paper doesn't differentiate between business sizes or employment types.

### C. Societal Questions

**[6_inequality]** Is income and wealth inequality across different sectors and regions affected? Directly addressed with strong evidence. The paper shows that automation will exacerbate income inequality by targeting low-wage, low-skill jobs while protecting high-wage, high-education occupations.

> "Finally, we provide evidence that wages and educational attainment exhibit a strong negative relationship with the probability of computerisation." (p. 41)

> "Our model predicts a truncation in the current trend towards labour market polarisation, with computerisation being principally confined to low-skill and low-wage occupations." (p. 44)

> "We note that this finding implies a discontinuity between the nineteenth, twentieth and the twenty-first century, in the impact of capital deepening on the relative demand for skilled labour." (p. 44)

**[7_job_quality]** How is job quality and worker satisfaction affected, not just employment numbers? Not directly addressed - the paper focuses on job displacement rather than quality of remaining jobs.  

**[8_demographics]** Do different demographic groups (education, location, age, gender, ethnicity, immigration) experience automation differently? Partially addressed through education lens. The limitation is the paper doesn't directly address age or geographic differences, focusing primarily on educational attainment as a demographic factor.

> "We do the same for skill level, measured by the fraction of workers having obtained a bachelor's degree, or higher educational attainment, within each occupation." (p. 41)

> "Bachelor's degree or better Probability of Computerisation 0 0.5 1 0% 20% 40% 60%" (p. 41, Figure IV)

**[9_mitigation]** What policies and interventions could be most effective at mitigating the negative impacts of automation? Not directly addressed - The paper focuses on technological capabilities rather than policy solutions. However, it does mention:

> "Second, regulatory concerns and political activism may slow down the process of computerisation." (p. 42)

> "The states of California and Nevada are, for example, currently in the process of making legislatory changes to allow for driverless cars." (p. 42)

**[10_societal]** What are the environmental and social costs of automation that aren't captured in economic metrics? Not addressed - The paper focuses purely on employment and economic metrics, not environmental or broader social impacts.