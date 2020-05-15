# Student Notes 

Dear Reviewer,
Here I am ensuring the availability of the following link i submitted for my project, please review this project.
#### GitHub Repository (Capstone Project) Link:

                https://github.com/abhishekpandeyIT/CapstoneProject.git


# CapstoneProject
 Covid-19 Outbreak Prediction Using Machine Learning using the Datasets upto 25th March.

 Its 25th March Afternoon and India has reported its 9th death with 562 total confirmed cases due to COVID-19. Fresh cases from Manipur, Bihar, Gujrat, and Madhya Pradhesh have been reported by the Union Ministry of Health and Family Welfare.

We need a strong model that predicts how the virus could spread across different countries and regions. The goal of this task is to build a model that predicts the spread of the virus in the next 7 days.

This Model prediction might not be 100% accurate but it predict the flow of spread of virus infection.

# Libraries used: 

#       For Data Manipulation
        import pandas as pd

#       Visualisation libraries
        import matplotlib.pyplot as plt
        %matplotlib inline 
        import seaborn as sns
        import plotly.express as px
        import plotly.graph_objects as go
        import folium 
        from folium import plugins

#       Manipulating the default plot size
        plt.rcParams['figure.figsize'] = 10, 12

#       Disable warnings 
        import warnings
        warnings.filterwarnings('ignore')

# Why Folium used?

Folium makes it easy to visualize data that's been manipulated in Python on an interactive Leaflet map. It enables both the binding of data to a map for choropleth visualizations as well as passing Vincent/Vega visualizations as markers on the map.

# Present Condition of Corona Infection:
 ##     World:

Coronavirus Cases:4,543,060
Deaths: 303,707
Recovered:1,712,895

 ##     India:
Coronavirus Cases:82,264
Deaths:2,649
Recovered:28,086


# Symptoms of Corona

    COVID-19 affects different people in different ways. Most infected people will develop mild to moderate illness and
    recover without hospitalization.
##  Most common symptoms:
        1. fever
        2. dry cough
        3. tiredness
        4. Less common symptoms:
        5. aches and pains
        6. sore throat
        7. diarrhoea
        8. conjunctivitis
        9. headache
        10.loss of taste or smell
        11.a rash on skin, or discolouration of fingers or toes
##  Serious symptoms:
        1. difficulty breathing or shortness of breath
        2. chest pain or pressure
        3. loss of speech or movement
        4. Seek immediate medical attention if you have serious symptoms. Always call before visiting your doctor or health facility.
        5. People with mild symptoms who are otherwise healthy should manage their symptoms at home.
        6. On average it takes 5–6 days from when someone is infected with the virus for symptoms to show, however it can take up to 14 days.

## Stay Safe, Stay Home.