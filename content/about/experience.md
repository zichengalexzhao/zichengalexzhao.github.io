---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Data Analyst, Practicum Project
    company: Alexander Tutoring
    company_url: 'https://alexandertutoring.com/'
    company_logo: custom/at
    location: San Francisco, CA
    date_start: '2024-08-01'
    date_end: ''
    description: |2-
        *Python, R, SQL, Machine Learning(K-Means, Logistic Regression)*
        
        * Explored and processed a 20K+ rows dataset, resolving data-mapping issues from different data sources including Stripe payment and Google Calendar data to ensure data integrity and drive accurate insights

        
        * Established a data analytics framework and built a churn model(AUC = 0.74) by Weighted Logistic Regression to calculate key KPIs, including a 68% churn rate and revenue trends

        
        * Developed a K-means clustering model (Machine Learning) to segment customers by payment behavior, identifying high, moderate, and low spenders


        * Built a star tutoring evaluation model using Principal Component Analysis for feature weighting and a random forest algorithm, incorporating key metrics such as rescheduling rates, conversion rates, churn, and customer lifetime value


        * Developed and automated data pipelines using Python and Google Cloud, integrated data into Salesforce, and created reports and interactive Salesforce dashboards to visualize 6 key metrics like churn rate etc., enhancing data-driven decision-making



        

  - title: Marketing Analyst
    company: Shell (China) Limited
    company_url: 'https://www.shell.com.cn/en_cn.html'
    company_logo: custom/shell
    location: Xiamen, CHN
    date_start: '2023-12-01'
    date_end: '2024-05-31'
    description: |2-
        *Python, A/B Testing, Power BI, Markeing Analysis*
        
        * Applied A/B testing and statistical methods to evaluate and refine digital marketing strategies, resulting in a 12% improvement in campaign conversion rates and enhanced customer segmentation

        
        *	Developed and deployed regression and classification models to forecast campaign outcomes, integrating diverse data sources into interactive dashboards that provide real-time performance metrics

        
  - title: Data Analyst, Internship
    company: Ningbo Powerhouse Capital LLP
    company_url: 'https://www.shell.com.cn/en_cn.html'
    company_logo: org-x
    location: Ningbo, CHN
    date_start: '2023-09-01'
    date_end: '2023-12-31'
    description: |2-
        *Python, Advanced Excel, Tableau*
        
        * Utilized Python (Pandas, NumPy, scikit-learn) to mine and analyze large-scale financial datasets, developing regression and time series models that enhanced revenue forecasting accuracy by 18%

        
        *	Created visually driven reports on telecommunications industry trends by using Tableau. Simplified complex data insights for non-technical stakeholders, highlighting growth opportunities and risks over the next 3-4 years in China

        
  - title: Quantitative Research Intern
    company: IPSOS
    company_url: 'https://www.ipsos.com/en-us'
    company_logo: custom/ipsos
    location: Guangzhou, CHN
    date_start: '2023-04-01'
    date_end: '2023-08-31'
    description: |2-
        *Python, A/B Testing, Statistical Analysis, SQL, Advanced Excel*
        
        * Conducted A/B testing and statistical analysis using Python to evaluate the effectiveness of various marketing strategies—resulting in an 8% increase in customer engagement in DiDi’s South American market

        
        *	Developed a comprehensive brand map by deploying Principal Component Analysis (PCA) to analyze DiDi’s and competitors’ brand perceptions(e.g. Uber), resulting in tailored strategic recommendations that enhanced market positioning

        
        *	Executed a conjoint analysis to quantify consumer willingness-to-pay for key ride features (e.g., comfort, price, safety), providing robust evidence that enabled DiDi’s pricing team to optimize dynamic pricing strategies

        

design:
  columns: '1'
---
