# BC AI Public Hackathon 3: Sea Group

## Team Members
- **Nguyen Mai Dinh Le (Demi Le)** – Data Analyst & Visualization Engineer  
- **Nichanun Pongpattarawit (Luck)** – Software Enginner  
- **Sotheng Chheang** - Software Enginner  

---
**YouTube**: https://www.youtube.com/watch?v=dA8E4Uj_0RY
**Comic book**: https://heyzine.com/flip-book/2a55214c04.html
---
## Project Overview

This project explores public perceptions of Artificial Intelligence (AI) in British Columbia through a comprehensive analysis of survey responses from over 900 residents. Our goal is to uncover how age, location, and personal experience shape attitudes toward AI, and to inform ethical, inclusive policy development. By combining quantitative analysis with qualitative insights from responses, we reveal key patterns in public sentiment, concerns, and hopes for AI’s future.

We found a clear generational divide: younger adults (18–34) are more likely to be regular AI users and view it as a creative or educational tool, while those aged 55+ express greater concern about job displacement and loss of human control. Interestingly, misinformation is a growing concern among youth, surpassing job loss in priority—highlighting their awareness of deepfakes and algorithmic manipulation on social media. Meanwhile, rural residents show slightly lower AI adoption but share similar levels of concern, especially around environmental impact and economic disruption.

The majority of respondents adopt a neutral or mixed stance, emphasizing that AI’s impact depends on responsible governance. Only 13% expressed strongly positive views, often calling for AI in healthcare and education, while 52% voiced negative sentiments, citing distrust in tech companies and fear of automation. Notably, those with hands-on AI experience tend to be less fearful, suggesting that access and literacy reduce anxiety.

Our analysis underscores the need for targeted AI literacy programs, inclusive public consultation, and balanced regulation. We recommend that BC prioritize transparency, equity, and environmental sustainability in AI policy. By listening to diverse voices—from urban developers to rural skeptics—we can build an AI future that reflects the values of all British Columbians.

---

## Tech Notes

This project combines data science, visualization, and multimedia storytelling to analyze survey data on AI adoption in British Columbia and transform insights into an engaging comic-style narrative.

---

### Data Analysis Workflow

#### 1. Survey Data Collection
- Dataset includes demographics (age, location, AI experience), multiple-choice responses, and open-ended text inputs.

#### 2. Data Cleaning and Transformation
- Preprocessing with **pandas**.  
- Standardized categorical variables (AI experience, sentiment labels).  
- Shortened long-form responses by extracting text before dashes in labels.  

#### 3. Sentiment Analysis
- Used precomputed sentiment scores (0–1).  
- Categories:  
  - Negative: 0–0.4  
  - Neutral: 0.4–0.6  
  - Positive: 0.6–1.0  
- Validated with keyword-based thematic tagging (regex on terms like *“job loss”* and *“fake news”*).  

#### 4. Visualization
- Built **bar charts, pie charts, and heatmaps** with matplotlib and seaborn.  
- Supplemented with **Tableau dashboards** for interactive storytelling.  
- Cross-tabulated results (e.g., AI experience × age group, sentiment × location).  
- Key finding: Non-users and rural respondents expressed more negative views.  

---

### Comic Book Creation Workflow

#### 1. Data-to-Story Translation
- Selected key insights from analysis.  
- Drafted a script with characters (Demi, Luck, Prof. Kris).  
- Refined dialogue using **ChatGPT**.  

#### 2. Visualization and Media Assets
- Generated illustrations and images with **ChatGPT image tools**.  

#### 3. Audio and Video Production
- Created AI voiceovers with **CapCut**.  
- Combined narration and visuals in **iMovie**.  

#### 4. Publishing Formats
- Uploaded video to **YouTube**.  
- Published flipbook version on **Heyzine**.  
- Shared outputs as both video and digital comic book.  

---

### Tools Used
- **Python** (pandas, matplotlib, seaborn)  
- **Tableau**  
- **Jupyter Notebook**  
- **OpenAI GPT**  
- **CapCut**  
- **Heyzine**  
- **iMovie**  

---

### Key Takeaway
This project demonstrates how mixed-method analysis and storytelling can transform survey data into **actionable and accessible multimedia formats**. It bridges technical analysis with creative communication, making complex AI issues understandable to a wider audience.


