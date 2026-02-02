# Netflix Content Analytics & Recommendation System

This project explores how content analytics and recommendation systems can be used to improve user engagement and content discovery on streaming platforms. Using a publicly available Netflix dataset, I combined exploratory data analysis, machine learning, and interactive dashboards to analyze content trends and build a recommendation framework.

---

## Project Overview

Streaming platforms rely heavily on personalization to drive engagement and retention. The goal of this project was to:

- Analyze Netflix’s content catalog to identify trends and patterns  
- Build a recommendation model to surface relevant titles based on content similarity  
- Create an interactive dashboard to support exploration and decision-making  

The project demonstrates an end-to-end analytics workflow, from data exploration and feature engineering to modeling and visualization.

---

## Data

The analysis uses a publicly available Netflix dataset containing metadata on titles, including:

- Genre  
- Release year  
- Country  
- Rating  
- Content type (Movie or TV Show)  

The dataset was used for both exploratory analysis and feature engineering for the recommendation model.

---

## Methodology

### Exploratory Data Analysis
- Analyzed content distribution by genre, release year, and content type  
- Identified catalog growth trends and shifts in content strategy  
- Examined relationships between content attributes to inform modeling decisions  

### Recommendation System
- Built a collaborative filtering–based recommendation model  
- Applied statistical modeling techniques to score content similarity  
- Generated top-N recommendations based on inferred user preferences  

### Visualization
- Designed an interactive Tableau dashboard to explore content trends and contextualize recommendations  
- Enabled filtering by genre, release year, and content type for stakeholder exploration  

---

## Tools & Technologies

- Python  
- TensorFlow  
- Pandas  
- Jupyter Notebook  
- Tableau  

---

## Deliverables

- **Tableau Dashboard**  
  https://public.tableau.com/app/profile/miriamgarcia/viz/NetflixContentAnalyticsDashboard_17492312134690/Homepage  

- **Source Code**  
  This repository contains the full exploratory analysis and recommendation model implementation.

---

## Key Insights

- Certain genres and content types dominate catalog growth, reflecting strategic investment areas  
- Content similarity and clustering can be leveraged to improve content discovery  
- Pairing machine learning outputs with dashboards improves interpretability and usability for non-technical stakeholders  

---

## Future Improvements

- Incorporate user-level behavioral data such as watch history and completion rates  
- Evaluate recommendation impact using A/B testing and experimentation frameworks  
- Extend the model to support real-time or near real-time recommendation pipelines  

---

## Notes

This project is for educational and portfolio purposes and uses publicly available data.  
It is not affiliated with or endorsed by Netflix.
