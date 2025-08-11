# NetflixTrendsandAnalysis: Content Engagement & Viewer Preferences

**Author:** Darious Brown  
**GitHub:** [Dare215](https://github.com/Dare215)  
**Email:** dariousbrown3@icloud.com  

## 1) Project Overview
NetflixTrendsandAnalysis explores global viewing habits and engagement patterns using Netflix Top 10 datasets.  
The objective is to identify trends in content engagement, analyze the performance of titles over time, and provide strategic recommendations for maximizing profits and customer retention.

## 2) Dataset
- **Source:** Netflix Top 10 global rankings and viewing hours datasets  
- **Files:**  
  - `NetfixConsumerStudy.ipynb`  
  - Netflix-provided CSV/Excel datasets (Top 10 titles, watch hours, content metadata)  
- **Key Variables:** `Title`, `Category`, `Release Date`, `Hours Viewed`, `Runtime`, `Country`

## 3) Key Features
- **Engagement Analysis:** Identify peaks in viewer engagement based on title release and promotional campaigns.
- **First 91-Day Performance:** Study how early viewership predicts long-term success.
- **Runtime Trends:** Compare average runtimes for movies vs. TV shows.
- **Geographic Insights:** Determine regions with the highest recurring title appearances.

## 4) Project Structure
```
NetflixTrendsandAnalysis/
│── NetfixConsumerStudy.ipynb   # Jupyter Notebook with analysis & visuals
│── Netfflix.docx               # Written audience-focused summary
│── datasets/                   # Netflix Top 10 datasets
│── README.md                   # Documentation
```

## 5) How to Run

### Option A — Python / Terminal
```bash
# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook "NetfixConsumerStudy.ipynb"
```

### Option B — PyCharm
1. Open folder in PyCharm  
2. Configure Python interpreter (point to `.venv`)  
3. Install dependencies from `requirements.txt`  
4. Run the notebook

## 6) Results Summary
- Engagement spikes when blockbuster shows are released or renewed.
- Titles with strong early (first 91 days) performance tend to retain higher long-term engagement.
- TV shows have more consistent runtimes and engagement than movies.
- Longer retention of high-performing titles could boost sustained profits.
- Marketing focus during the first 3 months after release maximizes title success.

## 7) Ethical Considerations
- Ensure viewer privacy when using streaming data.
- Avoid regional bias in content recommendations.
- Maintain transparency in engagement-based marketing.

## 8) Future Enhancements
- Develop predictive models for title engagement forecasting.
- Expand analysis to other streaming platforms for competitive insights.
- Incorporate social media sentiment to complement viewing data.

## 9) License
MIT License — Free to use with attribution.
