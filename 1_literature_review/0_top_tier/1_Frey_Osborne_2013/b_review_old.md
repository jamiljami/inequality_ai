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

## -------------------- Methodology ------------------
1. Task-based analysis: They identified engineering bottlenecks that prevent automation:
    - Perception and manipulation tasks (robots struggle with unstructured environments)
    - Creative intelligence tasks (difficult to encode creative values)
    - Social intelligence tasks (challenges in real-time emotion recognition)
2. Machine learning approach: Used ONET data (9 variables) to train a classifier on 70 hand-labeled occupations, then predicted automation probability for all 702 occupations

## -------------------- Scope Points ------------------

### Key Insights:
[2_automatable/]:
- High-risk occupations: Transportation/logistics, office/administrative support, production workers
- Surprisingly vulnerable: Service occupations (where most US job growth occurred)
- Protected occupations: Those requiring creative/social intelligence (engineers, scientists, healthcare workers, educators)
- Big Players: Google (autonomous vehicles), Amazon (Kiva warehouse systems), Baxter (general-purpose robots)
- Frontier Technologies: Autonomous vehicles, service robots, general-purpose robotics
- Engineering Bottlenecks: Perception/manipulation in unstructured environments, creative intelligence encoding, social intelligence recognition

[3_effects/]: 
- Wage polarization: Low-skill/low-wage jobs most at risk
- Educational protection: Higher education correlates with lower automation risk
- Historical shift: Unlike 19th century (deskilling) and 20th century (middle-skill hollowing), 21st century automation targets low-skill jobs
- Business Competition: Cost reduction through automation, productivity gains
- Employment Impact: 47% of US jobs at high risk of automation
- Worker Adaptation: Need for creative and social skills to remain competitive

[4_experiments/]:
- Methodology innovation: First quantitative study of future automation potential
- Engineering bottlenecks: Identified specific technical barriers to automation
- Task restructuring: Showed how tasks can be simplified to enable automation (e.g., prefabrication in construction)
- Two-Wave Model: First wave targets routine tasks, second wave depends on perception/manipulation breakthroughs
- Business Operation Framework: Analyzes employment, competition, customer, and revenue/cost effects

[5_conclusions/]:
- Speed of Progress: 47% of US jobs at risk, with rapid growth in service/industrial robots (20% annual growth, 166k units sold in 2011) and Chinese market (>50% growth in 2011)
- Business/Competition Effects: Businesses gain cost reductions and productivity through robot adoption, following a two-wave automation model (routine tasks then perception tasks) enabled by task restructuring
- Employment/Market Effects: Low-skill jobs face highest automation risk, requiring workers to develop creative/social skills while education provides some protection against displacement
- Key Technical Insights: Engineering bottlenecks exist in perception/creativity/social intelligence, while algorithms and robots rapidly expand into information processing, manufacturing, and service domains

### [2_automatable/] What is currently automatable?

#### Current Automation Capabilities

> Digital/Text/Code: "Algorithms for big data are now rapidly entering domains reliant upon storing or accessing information" (p. 37)

> Physical/Manual: "Robots will likely continue to take on an increasing set of manual tasks in manufacturing, packing, construction, maintenance, and agriculture" (p. 807)

> Service Tasks: "Robots are already performing many simple service tasks such as vacuuming, mopping, lawn mowing, and gutter cleaning" (p. 808)

#### Big Players Identified:

> Western: Google (autonomous driverless cars), Amazon (Kiva Systems for warehouse automation), Baxter (low-priced general-purpose robots)

> Global: "Robot sales in China grew by more than 50 percent in 2011" (p. 801), "Globally, industrial robot sales reached a record 166,000 units in 2011" (p. 802)

#### **Frontier/Cusp Technologies:**

> Autonomous Vehicles: "The autonomous driverless cars, developed by Google, provide one example of how manual tasks in transport and logistics may soon be automated" (p. 3)

> Service Robots: "Commercial service robots are now able to perform more complex tasks in food preparation, health care, commercial cleaning, and elderly care" (p. 809)

> General-Purpose Robots: "Low-priced general-purpose models, such as Baxter, are adopted in simple manufacturing and service work" (p. 803)

#### **Engineering Bottlenecks (What's NOT Automatable):**

> Perception and Manipulation: "Robots are still unable to match the depth and breadth of human perception" (p. 24)

> Creative Intelligence: "The principal obstacle to computerising creativity is stating our creative values sufficiently clearly that they can be encoded in a program" (p. 26)

> Social Intelligence: "The real-time recognition of natural human emotion remains a challenging problem" (p. 26)

### [3_effects/] What are the current effects?
#### **Business Competition Effects:**

> Cost Reduction: "As robot costs decline and technological capabilities expand, robots can thus be expected to gradually substitute for labour in a wide range of low-wage service occupations" (p. 810)

> Productivity Gains: "The market for personal and household service robots is growing by about 20 percent annually" (p. 809)

#### **Employment Effects:**

> 47% High Risk: "According to our estimate, 47 percent of total US employment is in the high risk category" (p. 37)

> Wage Polarization: "Wages and educational attainment exhibit a strong negative relationship with the probability of computerisation" (p. 41)

> Historical Shift: "Our model predicts a truncation in the current trend towards labour market polarisation, with computerisation being principally confined to low-skill and low-wage occupations" (p. 44)

#### **Worker Adaptation:**

> Skill Reallocation: "Low-skill workers will reallocate to tasks that are non-susceptible to computerisation – i.e., tasks requiring creative and social intelligence" (p. 44)

> Educational Protection: "High-skill and high-wage occupations are the least susceptible to computer capital" (p. 41)

#### **Social Effects:**

> Unemployment Risk: "Most workers in transportation and logistics occupations, together with the bulk of office and administrative support workers, and labour in production occupations, are at risk" (p. 43)

> Service Sector Vulnerability: "A substantial share of employment in service occupations, where most US job growth has occurred over the past decades, are highly susceptible to computerisation" (p. 44)

### [4_experiments/] What is a thought experiment demonstration of an automated workplace?

#### **Methodology Innovation:**

> First Quantitative Study: "To our knowledge, no study has yet quantified what recent technological progress is likely to mean for the future of employment" (p. 3)

> Machine Learning Approach: "We implement a novel methodology to estimate the probability of computerisation for 702 detailed occupations, using a Gaussian process classifier" (p. 1)

#### **Engineering Bottlenecks Analysis:**

> Perception Challenges: "Tasks that relate to an unstructured work environment can make jobs less susceptible to computerisation" (p. 24)

> Manipulation Limitations: "The handling of irregular objects, for which robots are yet to reach human levels of aptitude" (p. 25)

> Creative Intelligence: "Occupations requiring a high degree of creative intelligence will be automated in the next decades" (p. 26)

#### **Task Restructuring Examples:**

> Construction Prefabrication: "Prefabrication, in which the construction object is partially assembled in a factory before being transported to the construction site, provides a way of largely removing the requirement for adaptability" (p. 23)

> Warehouse Navigation: "Kiva Systems, acquired by Amazon.com in 2012, solved the problem of warehouse navigation by simply placing bar-code stickers on the floor" (p. 25)

#### **Two-Wave Automation Model:**

> First Wave: "Most workers in transportation and logistics occupations, together with the bulk of office and administrative support workers, and labour in production occupations, are likely to be substituted by computer capital" (p. 37)

> Second Wave: "The computerisation of occupations in the medium risk category will mainly depend on perception and manipulation challenges" (p. 39)

#### **Business Operation Analysis Framework:**
The paper provides a framework for analyzing automation effects across:
- Employment Effects: Detailed breakdown by occupation category
- Business Competition: Cost reduction through automation
- Customer Effects: Service quality changes through automation
- Revenue/Cost Analysis: Implicit in the focus on low-wage job displacement

### [5_conclusions/] What can we conclude from all of this?

#### **Speed of Progress:**
- Automation is accelerating beyond routine manufacturing tasks to include service and manual occupations
- Technology is advancing faster than worker adaptation capabilities
- The pace of innovation suggests rapid disruption across multiple sectors

#### **Effects on Businesses and Competition:**
- Cost Reduction: Automation provides significant cost advantages through labor substitution
- Productivity Gains: Growing market for service robots (20% annual growth)
- Competitive Pressure: Companies adopting automation gain competitive advantages
- Industry Transformation: Traditional service sectors becoming vulnerable to automation

#### **Effects on Employment and Markets:**
- Massive Displacement: 47% of US employment at high risk of automation
- Wage Polarization: Low-skill, low-wage jobs most vulnerable, creating inequality
- Educational Protection: Higher education provides significant protection against automation
- Skill Reallocation: Workers must transition to creative and social intelligence tasks

#### **Market and Industry Implications:**
- Service Sector Vulnerability: Areas of recent job growth (service occupations) are now at risk
- Transportation Disruption: Autonomous vehicles threaten entire transportation/logistics sector
- Office Automation: Administrative and clerical work highly susceptible
- Manufacturing Evolution: Continued automation in production with new capabilities

#### **Policy and Adaptation Challenges:**
- Regulatory Lag: Current regulations may slow but not prevent automation
- Worker Retraining: Massive need for skill development and education
- Inequality Exacerbation: Automation likely to increase economic disparities
- Social Disruption: Potential for significant unemployment and social unrest

#### **Research and Methodology Contributions:**
- Novel Framework: First quantitative methodology for measuring automation risk
- Comprehensive Analysis: 702 occupations analyzed with machine learning approach
- Predictive Model: Provides basis for future automation impact studies
- Engineering Insights: Identified specific technical barriers and opportunities

#### **Future Research Directions:**
- Timeline Predictions: Need for more precise automation timeline estimates
- Policy Analysis: Research on effective mitigation strategies
- Regional Variations: Geographic differences in automation impact
- Sector-Specific Studies: Detailed analysis of individual industry impacts

## -------------------- Research Questions ------------------

### A. Methodological Questions

**[1_measurement]** How can we measure the true economic impact of automation beyond simple job displacement? Directly addressed and a key contribution.

> "To our knowledge, no study has yet quantified what recent technological progress is likely to mean for the future of employment. The present study intends to bridge this gap in the literature." (p. 3)

> "We make no attempt to estimate how many jobs will actually be automated. The actual extent and pace of computerisation will depend on several additional factors which were left unaccounted for." (p. 41)

Methodology innovation:

> "We implement a novel methodology to estimate the probability of computerisation for 702 detailed occupations, using a Gaussian process classifier." (p. 1)

**[2_sources_and_metrics]** What data sources and metrics are most reliable for tracking automation's effects on inequality? Directly addressed.

> "Accordingly, ONET has the advantage of providing more recent information on occupational work activities." (p. 4)

> "We rely on the 2010 version of the DOT successor ONET – an online service developed for the US Department of Labor." (p. 4)

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