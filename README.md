NetflixTrendsAnalysis – Global Netflix Top 10 Content Analytics
Author: Darious Brown
GitHub: https://github.com/Dare215
LinkedIn: https://www.linkedin.com/in/dariousbrown
Portfolio: https://dare215.github.io/DariousBrown-Portfolio/
Email: dariousbrown3@icloud.com
Project Overview
NetflixTrendsAnalysis explores global Netflix Top 10 content performance using data analytics, statistical visualization, and exploratory data analysis (EDA).
The project examines audience engagement, content popularity, viewing behavior, runtime characteristics, and performance trends across Netflix's most watched television programs. By transforming raw streaming metrics into actionable insights, this analysis demonstrates how data science can be applied within the entertainment and media industry.
The objective was to identify relationships between content rankings, runtime, audience engagement, and viewing hours while uncovering patterns that drive global streaming success.
Business Problem
Streaming platforms generate massive amounts of audience engagement data every day.
Questions addressed include:
What content attracts the largest audiences?
How does runtime influence viewing behavior?
What relationships exist between rankings and audience engagement?
Which shows dominate long-term viewership?
How do weekly viewing patterns fluctuate over time?
Understanding these factors can help support:
Content acquisition decisions
Marketing strategies
Audience retention initiatives
Recommendation systems
Forecasting future content performance
Dataset
The dataset contains Netflix Top 10 global content performance metrics, including:
Show title
Weekly viewing hours
First 91-day viewing metrics
Content ranking
Runtime
Content category
Release performance indicators
The dataset was cleaned and transformed for exploratory analysis and visualization.
Methodology
Data Preparation
Imported Netflix Top 10 datasets
Cleaned missing values
Standardized content categories
Validated viewing metrics
Prepared data for analysis
Exploratory Data Analysis (EDA)
Weekly viewership trends
Runtime analysis
Distribution analysis
Popularity rankings
Correlation analysis
Statistical Analysis
Correlation matrix development
Runtime comparisons
Audience engagement evaluation
Content performance assessment
Visualization Development
Multiple visualizations were developed to identify:
Viewership trends
Runtime behavior
Audience engagement patterns
Popularity rankings
Statistical relationships
Visual Analysis
Project Overview Visualization
Netflix Trends Analysis
This visualization provides a high-level overview of weekly global Netflix viewing activity and highlights fluctuations in audience engagement over time.
Most Watched Netflix Shows (First 91 Days)
This chart highlights the highest-performing Netflix titles based on first 91-day viewing hours.
Key Insight
Squid Game remains the dominant global performer.
Wednesday and Stranger Things demonstrate exceptional audience retention.
Several series exceed one billion viewing hours within the first 91 days.
Runtime Distribution by Content Type
This boxplot compares runtime distributions between English and Non-English Netflix content.
Key Insight
English-language content generally demonstrates longer average runtimes.
Non-English content shows greater variability across titles.
Runtime differences may influence viewer engagement behavior.
Weekly Viewing Hours Distribution
This histogram examines the distribution of weekly viewing hours across top Netflix content.
Key Insight
Most content clusters around moderate viewing levels.
A small number of blockbuster titles generate exceptionally high audience engagement.
Viewing activity displays positive skewness.
Correlation Analysis
The correlation heatmap examines relationships among:
Rank
Runtime
Hours Viewed
First 91-Day Views
Key Findings
Strong positive relationship between viewing hours and total views.
Higher-ranked content receives substantially greater audience engagement.
Runtime demonstrates a moderate relationship with viewing behavior.
Popularity metrics exhibit significant correlation.
Key Findings
Audience Behavior
A relatively small number of shows generate the majority of viewing activity.
Audience engagement concentrates around highly promoted content.
Content Performance
Squid Game remains one of Netflix's strongest-performing global releases.
Several blockbuster series consistently dominate rankings.
Runtime Effects
Runtime alone is not a primary driver of success.
Content quality and audience appeal appear more influential.
Statistical Relationships
Hours viewed and total views demonstrate strong correlation.
Ranking performance strongly aligns with audience engagement metrics.
Business Impact
This project demonstrates how streaming analytics can support decision-making across media organizations.
Potential applications include:
Content strategy optimization
Audience engagement analysis
Recommendation system enhancement
Marketing campaign planning
Content investment decisions
Forecasting viewer demand
Subscription retention initiatives
Skills Demonstrated
Data Science
Exploratory Data Analysis (EDA)
Statistical Analysis
Correlation Analysis
Trend Analysis
Data Visualization
Histograms
Boxplots
Correlation Heatmaps
Time-Series Analysis
Ranking Visualizations
Python Analytics
Pandas
NumPy
Matplotlib
Seaborn
Business Intelligence
Streaming Analytics
Audience Behavior Analysis
Content Performance Evaluation
Decision Support Analytics
Repository Structure
NetflixTrendsAnalysis/
│
├── notebook/
│   └── NetflixTrendsAnalysis.ipynb
│
├── visuals/
│   ├── NetflixTrendsAnalysisAI.png
│   ├── MostWatchedNetflixShows91Days.png
│   ├── NetflixRuntimeDistribution.png
│   ├── NetflixContentTypeDistribution.png
│   └── NetflixContentCorrelationHeatmap.png
│
├── data/
├── docs/
├── README.md
├── requirements.txt
└── .gitignore
Installation
git clone https://github.com/Dare215/NetflixTrendsAnalysis.git

cd NetflixTrendsAnalysis

pip install -r requirements.txt

jupyter notebook
Open:
notebook/NetflixTrendsAnalysis.ipynb
Future Improvements
Potential future enhancements include:
Predictive viewership forecasting
Recommendation system modeling
Time-series forecasting
Audience segmentation
Streamlit dashboard deployment
Power BI integration
Interactive analytics applications
Author
Darious Brown
PhD Candidate – Artificial Intelligence & Machine Learning
DBA Candidate
Data Scientist | Machine Learning Engineer | AI Researcher
Professional Profiles
GitHub: https://github.com/Dare215
LinkedIn: https://www.linkedin.com/in/dariousbrown
Portfolio: https://dare215.github.io/DariousBrown-Portfolio/
Email: dariousbrown3@icloud.com
Areas of Expertise
Artificial Intelligence
Machine Learning
Deep Learning
Generative AI
Natural Language Processing
Computer Vision
Predictive Analytics
Data Science
Financial Analytics
Healthcare Analytics
Manufacturing Analytics
License
This project is intended for educational, research, and portfolio demonstration purposes.
