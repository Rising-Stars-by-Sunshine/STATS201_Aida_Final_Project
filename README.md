# Fueling Development: Examining Economic Drivers of Energy Access and Efficiency
## Project Information

- **Author**: Aida Camacho Ponce de Leon, Computation & Design with a track in Social Policy, Class of 2026, Duke Kunshan University.

- **Instructor**: Professor Luyao Zhang, Duke Kunshan University

- **Disclaimer**: Submissions to the Final Project for STATS 201: Intorduction to Machine Learning for Social Science at Duke Kunshan University.

- **Acknowledgments**: I extend my sincere gratitude to Professor Luyao (Sunshine) Zhang for her invaluable supervision
and insightful teaching during the STATS 201 machine learning for social science course. Her guidance and support were
instrumental in shaping the development of this project. Additionally, I would like to express my thanks to my peers in
STATS 201 for fostering a collaborative environment that greatly enriched my educational journey.

- **Project Summary**:
<p align="center">
  <kbd>
    <img src="Research_mindmap.png" alt="Flowchart2" width="600"/>
  </kbd>
</p>

*Figure 1: Map of the research proposal. Created with Whimsical*

### Background/Motivation
This research explores the intricate relationship between economic factors and energy efficiency using machine learning techniques. By analyzing data on energy consumption, production, and economic indicators, we aim to uncover patterns and insights that can inform policy decisions and infrastructure planning efforts. Our study addresses pressing questions about disparities in energy access and the determinants of countries' energy efficiency classifications. Through this research, we seek to contribute to the transition towards a sustainable global energy system. *Figure 1* shows a detailed flowchart of this summary, providing an overview of the research proposal.

While previous studies have examined energy consumption trends across different regions and countries, there is still a need for a more thorough analysis considering economic development levels and geographical regions. Additionally, understanding the specific impact of economic factors on energy access disparities and efficiency classifications remains an ongoing challenge in the literature. Furthermore, existing literature lacks a comprehensive understanding of how economic factors influence energy access and efficiency. Our research fills this gap by employing advanced machine learning techniques to analyze large datasets and uncover nuanced relationships.


### Research Questions
The research aims to answer the following questions:

- RQ1: How do economic factors such as GDP per capita correlate with energy access disparities across different regions?
- RQ2: What factors contribute to the classification of countries into high, medium, and low energy efficiency levels, and can these factors be used to predict a country's energy efficiency?

### Application Scenarios
The transition towards eco-friendly energy sources, coupled with global events like COP28, underscores the urgency of understanding energy patterns. This research aims to unravel the impact of economic variables on energy access and efficiency, addressing critical gaps in existing literature and offering insights into sustainable energy practices.

### Methodology
**Data Source and Datasets:**
Using the dataset on energy consumption and production by the scientific online site Our World in Data (2023), the research will integrate external datasets related to economic indicators, policy changes, and global events. The dataset provides a comprehensive overview of global energy dynamics, including variables related to energy consumption, production, and environmental impact. For example, country names, years, population, GDP, biofuel consumption, coal usage, gas consumption, nuclear power, oil consumption, hydropower, low-carbon energy, renewables, and others (Rosado et.al, 2023). Data preprocessing techniques will be employed to handle missing values and to filter only the necessary data.

**Machine Learning Algorithms:**
This research will employ advanced machine learning algorithms, including regression models and random forest classifiers, for analysis. The regression models will elucidate the relationship between economic factors and energy access disparities, while random forest classifiers will discern the key determinants of countries' energy efficiency classifications.

**Software and Computing Platforms:**
Python is the primary programming language, leveraging data analysis libraries such as Pandas and NumPy.


### Results
Anticipated outcomes include identifying specific economic factors influencing energy access disparities and elucidating the pivotal determinants of countries' energy efficiency classifications. These findings are poised to inform policy decisions, infrastructure planning endeavors, and risk management strategies, thereby facilitating the transition towards a sustainable and secure global energy system.

### Intellectual Merits/Practical Impacts
By enhancing our understanding of the intricate dynamics between economic variables and energy-related outcomes, this research endeavors to furnish policymakers, energy planners, and researchers with actionable insights to devise adaptive strategies, formulate inclusive policies, and design resilient energy infrastructures. Ultimately, this endeavor aims to contribute towards fostering global energy sustainability and resilience in the face of evolving economic landscapes and shifting global paradigms.

<p align="center">
    <img src="FP_DraftPoster.png" alt="Flowchart2" width="600"/>
</p>

*Figure 1: Poster of the Research Project. Created with Canva*


## Table of Contents

1. [About the Author](./README.md#about-the-author)
      - Headshot
      - Bio and Resume

2. [Literature](literature/Readme.md)
   - [1.1. Paper Analysis](./literature/Readme.md#11-paper-analysis)
      - Background/Motivation
      - Research Question
      - Application Scenarios
      - Methodology
      - Results
      - Intellectual Merits/Practical Impacts
   - [1.2. Research Idea](./literature/Readme.md#12-research-idea)
      - Background/Motivation
      - Research Question
      - Application Scenarios
      - Methodology
      - Results
      - Intellectual Merits/Practical Impacts

3. [Method](method/README.md)
   - [The Prediction Problem](./method/README.md#11-the-prediction-problem)
      - [Prediction Task Workflow](./method/README.md#prediction-task-workflow)
      - [Research Question Formulation](./method/README.md#research-question-formulation)
      - [Operational Measures](./method/README.md#operational-measures) 
      - [Hypothesis Development](./method/README.md#hypothesis-development)
   - [The Machine Leaning Workflow](./method/README.md#12-the-machine-learning-workflow)
      - [Model Development](./method/README.md#model-development) 
      - [Results Presentation](./method/README.md#results-presentation)
      - [Model Evaluation](./method/README.md#model-evaluation)   
      
4. [Data](data/README.md)
   - [Queried data](./data/Queried_data)
   - [Data Description](./data/README.md)
      - [Dataset Sturcture flowchart](./data/README.md#dataset-structure)
      - [Data Dictionary](./data/README.md#data-dictionary)
   - [Processed data](./data/Processed_data)

5. [Code](code/README.md)
   - [Data Query Process Description](./code/README.md#data-query)
      - [App of visualization 1](./code/README.md#visualization-1)
      - [App of visualization 2](./code/README.md#visualization-2)
      - [App of visualization 3](./code/README.md#visualization-3)
      - [Pseudo-code](./code/README.md#data-query-process-pseudo-code)
      - [Flowchart](./code/README.md#data-query-flowchart)
      - [References](./code/README.md#references)
   - [Data Query code](./code/data_query)
   - [Data Analysis](./code/data_analysis)
      - [Regression Data Processing](./code/data_analysis/Data_Processing_Regression.ipynb)
      - [Regression Data Analysis](./code/data_analysis/Data_Analysis_Regression.ipynb)
      - [Classification Data Processing and Analysis](./code/data_analysis/Analysis_Processing_Classification.ipynb)

