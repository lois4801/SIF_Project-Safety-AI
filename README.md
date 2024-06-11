# SIF_Project and Project-Safety-AI --- 2 LIVE END TO END PROJECT
A project to be presented to an Electric and Power Company namely Nova Scotia Power for Analyzing the variables and factors involving injuries and fatalities in Electrical Field Industry.  


# I. SIF Project
![electro-boom](https://github.com/lois4801/SIF_Project-Safety-AI/assets/96842662/c8bdd1ea-a023-4933-b037-43396834c14d)


- To research the necessary factors and variable that revolves around Electrical Field injuries and fatalities
- To analyze the schema and diagram for the SIF Project
- To create and design the database 
- To present different means of presenting data using Data Science techniques, programming
- To apply Data Analysis techniques and process like data cleaning, data munging, data wrangling, data manipulation
- To use PowerBI, Tableau, and Google Looker studio in presenting different aspects of data involving injuries and fatalities in Electrical Field Industry
- To create a website that enables the audience to see the output report of the data gathered
- To use API or hyperlinks to connect different platforms used from data gathering, data cleaning until data presentation
- To test the functionality of each dashboards
- To test the real time integration FROM WEBAPP TO MICROSOFT SOFTWARES >>>  FROM WEBAPP TO POWERPOINT PRESENTATION >>> FROM WEBAPP TO WEBAPP>>> FROM WEBAPP TO MY OWN CREATED WEBSITE
- To do data integration testing and data quality assusrance testing during the start of the project until it is finished
- Be sure to add description for each DASHBOARD FUNCTIONS.
- Be sure to interconnect each graphs in each dashboards especially in Tableau. 

## A. Introduction

SIF stands for Serious Injury and Fatality. SIF prevention methods are all about stopping these kinds of accidents from happening in the workplace.
There are a number of ways to achieve SIF prevention, and effective strategies typically involve a combination of approaches. 

## B. Key areas to focus on:

- Hazard Identification and Risk Assessment:
-- Proactive identification of high-energy hazards is crucial. This involves inspecting workplaces, reviewing past incidents, and understanding the tasks performed by workers. Once hazards are identified, steps can be taken to assess and mitigate the risks.

- Implementing Effective Safety Controls: 
-- There are two main types of controls: eliminating hazards altogether and implementing safeguards to minimize harm if an accident occurs. Examples include using guardrails when working at heights, ensuring proper ventilation when working with chemicals, and requiring workers to wear Personal Protective Equipment (PPE).

- Building a Strong Safety Culture:
-- This goes beyond just having rules in place. It's about creating an environment where everyone feels empowered to identify and report safety hazards, and where following safety procedures is the norm. This can be achieved through training, leadership commitment, and open communication.

- Data Analysis and Improvement:
-- Safety programs should be data-driven. By collecting and analyzing information on near misses and past incidents, organizations can identify trends and areas where they need to focus their SIF prevention efforts.

## C. Creating, Designing, Generating Database and Dataset
### 1. DATA Structure
### a. Incident ID
- Unique identifier for each incident

### b. DAte of Incident
- Data when the incident occured

### c. Location
- Specific location where the incident took place (eg. Substation, power plant, field site)

### d. Type of Incident
- Categorization of the incident (eg. Electrical shock, fall from height, equipment failure)

### e. Severity 
- Classification of the incident severity (serious, injury , fatality)

### f. Description of Incident
- Detailed description of what happened.

### g. Cause
- Root cause of the incident (e.g., human error, equipment malfunction, environmental factors).

### h. Victim Details
- Information about the victim(s) involved (e.g., job title, years of experience, age).

### i. Safety Equipment Used
- Personal protective equipment (PPE) used at the time of the incident (e.g., gloves, helmets, harness).

### j. Witnesses
- Names or number of witnesses to the incident.

### k. Investigation Findings
- Summary of findings from the incident investigation.

### l. Corrective Actions Taken
- Actions implemented to prevent recurrence of similar incidents.

### m. Reporting Agency
- The agency or authority to which the incident was reported (e.g., CCOHS , OSHA, local regulatory body).

### o. Legal Consequences
- Any legal actions or fines resulting from the incident.
----------------------------------------------------------------------------------------------------------------
## PROCESS PLAN OPTIONS
## PLAN 1
- Database to data ETL EXCEL to Tableau for Story Telling and presentation

## Plan 2
- Database creation- SQL Programming- Excel to Google Looker Studio

## Plan 3
- Excel to PowerBI for Presentation

## PLAN 4
- Excel to Python programming using Data Science and Data analysis processes and tools.

-------------------------------------------------------------------------------------------------------------

# Plan 1
- Unprocessed dataset
  https://drive.google.com/file/d/1jX81EraAeQRSsv_d-X6ojspXJuLxgOrk/view?usp=drive_link
- Cleaned and processed dataset
https://drive.google.com/file/d/19RNZWOXIB5q8gxm-EBhDmgk1LV3WHM_b/view?usp=sharing


### Data Cleaning Process
- Replaced OSHA to CCOHS to standardize the data
- Remove empty cells
- Removed the duplicates
  
![Screenshot 2024-06-10 195552](https://github.com/lois4801/SIF_Project-Safety-AI/assets/96842662/19c32458-6533-4d9a-8603-33a52ab913ae)

![Screenshot 2024-06-10 200227](https://github.com/lois4801/SIF_Project-Safety-AI/assets/96842662/75d97e3f-c484-4938-9365-947d2fa01b81)

![Screenshot 2024-06-10 210251](https://github.com/lois4801/SIF_Project-Safety-AI/assets/96842662/58378624-20cf-4101-89a7-b396af93be33)

### DATA ETL and Manipulation
- Importing the cleaned data to the tableau. Extracting the datasets and manipulating the necessary variables
![Screenshot 2024-06-10 211939](https://github.com/lois4801/SIF_Project-Safety-AI/assets/96842662/815a0187-1086-493f-a59b-1062817696d2)

- Manipulated my variables on my Tableau to suit to my needs to present different information by graphs on each sheet
  ![Screenshot 2024-06-11 024532](https://github.com/lois4801/SIF_Project-Safety-AI/assets/96842662/61d64a4e-6b49-4174-94d1-b5e400698b79)

![Screenshot 2024-06-11 024532](https://github.com/lois4801/SIF_Project-Safety-AI/assets/96842662/d41d0cda-171d-4586-8a07-8592fe2e45b6)

### DASHBOARD 1- 

<div class='tableauPlaceholder' id='viz1718086721883' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;SI&#47;SIFProject&#47;SIFProjectTableauPublicSeverityofEachIncidentEachYearDashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SIFProject&#47;SIFProjectTableauPublicSeverityofEachIncidentEachYearDashboard2' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;SI&#47;SIFProject&#47;SIFProjectTableauPublicSeverityofEachIncidentEachYearDashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1718086721883');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='1600px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='950px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='1600px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='950px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.minHeight='1300px';vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

------------------------------------------------------------------------------------------------------------- 
  
# II. Project Safety AI
- To use create a web based platform that aggregates data involving injuries and fatalities in Electrical Field Industry
- To apply data management and controls for the 3 to 4 projects under Project Safety AI
- To apply Machine Learning, NLP and LLM in creating models for the platform.
- To apply data quality, data testing, data programming
- To use quantitative and qualitative analysis that revolves around risk management and Job hazard management
- To create and design a web based data analysis platform that automatically produced graphs and charts based from the input of the user in real time
- To create and design a web based visual NLP task application



Embed Tableau to Powerpoint
https://www.vizwiz.com/2012/05/tableau-tip-embedding-dashboard-in.html
