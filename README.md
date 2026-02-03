## Aviation Safety Risk Analysis for Aircraft Procurement  
___
**Author**: Reeves Gonah  
**Date**:  
**Project**: Phase 1 End Project  
**Data Source**: [Aviation Safety Network (Scraped)](https://www.kaggle.com/datasets/anandkushawaha/aviation-crashed-flights-data)  
***
___
![alt text](takeoff.jpeg)

### **Project Overview**

As the organization considers expanding into the aviation sector, a key strategic decision is selecting aircraft that minimize operational and safety risk. This project analyzes historical aviation accident data to identify aircraft types, trends, and contributing factors associated with higher or lower accident risk.

Using the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework, this analysis applies exploratory data analysis and visualization techniques to support data-driven aircraft procurement decisions. The goal is to translate historical safety data into clear, actionable business recommendations.
___

### **Business Understanding**
#### **Business Context**

The company plans to enter the aviation market by purchasing and operating aircraft. Safety and operational risk are critical considerations, as accidents can result in financial losses, reputational damage, regulatory scrutiny, and operational disruption.

To support procurement strategy, this analysis focuses on identifying aircraft associated with lower accident frequency and severity.

#### **Business Objective**

Identify aircraft types that are associated with lower accident risk and severity, or good durability, in order to guide safer aircraft acquisition and operational planning.

**Key Business Questions**

This analysis is designed to answer the following business-driven questions:

*   How has accident risk changed over time?

*   Which aircraft or aircraft types are more prone to accidents?

*   Which aircraft provide the most safety and are the most durable in accidents?

**Success Criteria**

-> Clear identification of lower-risk and higher-risk aircraft categories

-> Evidence-based insights supported by visualizations

-> Three concrete, data-backed business recommendations to guide procurement decisions
___

### **Data Understanding**

The dataset contains historical records of aviation accidents, including information on:

* Aircraft make and model  
* Accident dates, airline operator and location  
* Accident Severity and outcomes (Fatalities)  

Initial data exploration included:  

* Inspection of data types and missing values  
* Summary statistics and frequency counts  
* Identification of key variables relevant to safety risk  

These steps ensured familiarity with the structure, limitations, and quality of the data before proceeding to cleaning and analysis.
___

### **Data Preparation**

Data preparation steps included:

*   Handling missing and inconsistent values

*   Cleaning categorical fields (e.g., aircraft and operator names)

*   Standardizing date field

*   Creating derived fields to support trend and grouping analysis

*   Filtering and aggregating data for clearer comparisons

All cleaning and transformation steps are documented in the Jupyter Notebook for transparency and reproducibility.
___

### **Analysis & Modeling (Exploratory)**

This project focuses on exploratory analysis rather than predictive modeling. Key analytical approaches include:

* ->Time-series analysis of accident trends

* ->Aggregation of accidents by aircraft type

* ->Comparison of accident frequency and severity by manufacturer

Visualizations are used to clearly communicate patterns and relationships that are relevant to business decision-making.
___

### **Evaluation**

Results were evaluated against the original business questions to ensure alignment with procurement objectives. Each key insight was assessed based on:

* *Relevance to aircraft selection decisions*

* *Strength and clarity of supporting evidence*

* *Practical interpretability for non-technical stakeholders*

*Limitations of the dataset and analysis assumptions are acknowledged in the notebook.
___

### **Key Findings & Recommendations**

Based on the analysis, the following high-level recommendations are provided:

*   Considering time-based safety trends, more recent operational periods reflect improved safety standards, incentivizing venture into aviation field.

*   Consider large manufacturers but whose models are less accident prone.

*   Prioritize aircraft types with consistently higher accident survival when making initial procurement decisions.
___

### **Additional Notes:**  

Full supporting analysis and visual evidence are provided in the notebook (index.ipnyb) and [Tableau Published Dashboard.](https://public.tableau.com/views/phase-1-project-dashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Additionally, presentation slides have been included in pdf format, as well as a pdf version of the index.ipnyb file.