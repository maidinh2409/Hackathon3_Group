# BC AI Public Hackathon3_Group

## Team Members
- **Nguyen Mai Dinh Le (Demi Le)** – Data Analyst & Visualization Engineer  
- **Nichanun Pongpattarawit (Luck)** – Software Enginner  
- **Sotheng Chheang** - Software Enginner  

---

## Project Overview

This project explores public perceptions of Artificial Intelligence (AI) in British Columbia through a comprehensive analysis of survey responses from over 900 residents. Our goal is to uncover how age, location, and personal experience shape attitudes toward AI, and to inform ethical, inclusive policy development. By combining quantitative analysis with qualitative insights from responses, we reveal key patterns in public sentiment, concerns, and hopes for AI’s future.

We found a clear generational divide: younger adults (18–34) are more likely to be regular AI users and view it as a creative or educational tool, while those aged 55+ express greater concern about job displacement and loss of human control. Interestingly, misinformation is a growing concern among youth, surpassing job loss in priority—highlighting their awareness of deepfakes and algorithmic manipulation on social media. Meanwhile, rural residents show slightly lower AI adoption but share similar levels of concern, especially around environmental impact and economic disruption.

The majority of respondents adopt a neutral or mixed stance, emphasizing that AI’s impact depends on responsible governance. Only 13% expressed strongly positive views, often calling for AI in healthcare and education, while 52% voiced negative sentiments, citing distrust in tech companies and fear of automation. Notably, those with hands-on AI experience tend to be less fearful, suggesting that access and literacy reduce anxiety.

Our analysis underscores the need for targeted AI literacy programs, inclusive public consultation, and balanced regulation. We recommend that BC prioritize transparency, equity, and environmental sustainability in AI policy. By listening to diverse voices—from urban developers to rural skeptics—we can build an AI future that reflects the values of all British Columbians.

---

## Tech Notes

This project leverages Python’s data science stack to analyze structured and unstructured survey data. The dataset, collected via an online form, includes demographic variables (age, location, AI experience), multiple-choice responses, and open-ended text inputs. We used `pandas` for data cleaning, transformation, and aggregation, ensuring consistency across categorical variables like AI experience and sentiment labels.

A key preprocessing step was shortening long-form AI experience labels (e.g., "Occasional user – I’ve tried a few tools...") by extracting text before the dash using string splitting. 

For sentiment analysis, we used precomputed sentiment scores (ranging 0–1) from the dataset, categorized into Negative (0–0.4), Neutral (0.4–0.6), and Positive (0.6–1.0). These were validated against keyword-based thematic tagging (e.g., “job loss”, “fake news”) using regex matching. Visualization was performed with `matplotlib` and `seaborn`, generating bar charts, pie charts, and heatmaps to illustrate disparities in AI adoption and concern across demographics.

We conducted cross-tabulations to examine AI experience by age group and sentiment by location, revealing that non-users and rural respondents are more likely to express negative views. All visualizations were designed for clarity and storytelling, aligning with narrative insights from character-driven analysis (Demi, Luck, and Prof. Kris).

The code is modular and reproducible, supporting future extensions such as predictive modeling of sentiment or integration with geospatial data. This project demonstrates how mixed-method analysis can turn survey data into actionable public policy insights.

Tools used: Python • JupyterNoteBook • OpenAI GPT • Canva •
