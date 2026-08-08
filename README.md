# 🐦 Twitter Sentiment Analysis Dashboard

An interactive **Twitter Sentiment Analysis Dashboard** built using **Microsoft Power BI** to analyze and visualize public sentiment from Twitter data. The dashboard provides insights into positive, negative, and neutral sentiments through interactive charts, KPIs, and filters.

## 📊 Dashboard Overview

The dashboard transforms Twitter sentiment data into meaningful visual insights, helping users understand overall public opinion, sentiment trends, and topic-wise sentiment distribution.

## ✨ Features

- 📈 Interactive sentiment analysis dashboard
- 😊 Positive, 😐 Neutral, and 😞 Negative sentiment classification
- 📊 Sentiment distribution visualization
- 📅 Sentiment trends over time
- 🔎 Interactive filters and slicers
- 📌 KPI cards for key metrics
- 🗺️ Location-based sentiment analysis
- 🔤 Word/keyword analysis
- 📱 User-friendly Power BI interface

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Excel / CSV**
- **Data Visualization**
- **Twitter Dataset**

## 📂 Project Structure

```text
Twitter-Sentiment-Dashboard/
│
├── dataset/
│   └── twitter_sentiment.csv
│
├── dashboard/
│   └── Twitter_Sentiment_Dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

## 🔄 Data Processing

The data was processed using **Power Query** before being visualized in Power BI.

### Data Preparation Steps

1. Imported Twitter dataset
2. Removed duplicate records
3. Handled missing values
4. Cleaned text and categorical fields
5. Transformed sentiment-related columns
6. Created calculated columns and measures using DAX
7. Built interactive dashboard visualizations

## 📌 Key KPIs

The dashboard can display important metrics such as:

- **Total Tweets**
- **Positive Tweets**
- **Negative Tweets**
- **Neutral Tweets**
- **Positive Sentiment %**
- **Negative Sentiment %**
- **Neutral Sentiment %**

## 📊 Dashboard Visualizations

The dashboard includes:

- 📊 Sentiment distribution chart
- 📈 Sentiment trend over time
- 📌 KPI cards
- 📉 Sentiment comparison
- 🌍 Location-based analysis
- 🔤 Keyword/word analysis
- 🎛️ Interactive slicers and filters

## 🧮 DAX

DAX measures were used to calculate important metrics and enable dynamic dashboard analysis.

Example:

```DAX
Total Tweets = COUNTROWS(Tweets)
```

```DAX
Positive Tweets =
CALCULATE(
    COUNTROWS(Tweets),
    Tweets[Sentiment] = "Positive"
)
```

```DAX
Negative Tweets =
CALCULATE(
    COUNTROWS(Tweets),
    Tweets[Sentiment] = "Negative"
)
```

## 🚀 How to Use

1. Download or clone this repository.

```bash
git clone https://github.com/yourusername/twitter-sentiment-dashboard.git
```

2. Open the `.pbix` file using **Microsoft Power BI Desktop**.

3. If required, update the dataset/file path in **Power Query**.

4. Refresh the data.

5. Use the dashboard's filters and slicers to explore sentiment insights.

## 🎯 Key Insights

The dashboard can be used to identify:

- Overall public sentiment
- Changes in sentiment over time
- Positive vs. negative sentiment patterns
- Most discussed topics or keywords
- Geographic sentiment patterns
- Trends in public opinion

## 🔮 Future Enhancements

- 🔴 Real-time Twitter/X data integration
- 🤖 Automated sentiment classification using Machine Learning
- 📡 Real-time Power BI dashboard updates
- ☁️ Power BI Service deployment
- 📱 Mobile-optimized dashboard
- 🔍 Advanced topic and hashtag analysis

## 📷 Dashboard Preview

Add your dashboard screenshot here:

```markdown
![Twitter Sentiment Dashboard](screenshots/dashboard.png)
```

## 👨‍💻 Author

**Raj**

Data Analytics | Power BI | Python | Machine Learning

⭐ If you found this project useful, consider giving the repository a star!
