# 🎵 Spotify 2024 Global Listener & Streaming Analysis

An end-to-end data analytics project exploring global music-streaming patterns across **500 market entries**. This project analyzes artist performance, regional streaming activity, genre-level listening behavior, skip rates, and Free-versus-Premium platform dynamics to develop actionable insights for music-platform strategy.

---

## 📌 Key Metrics & Findings

- **Total Streaming Volume:** 1.29 trillion streams
- **Reported Listening Time:** 4.79 million hours streamed
- **Top Artist by Streams:** BTS — 124.3 billion streams
- **Top Artist by Monthly Listeners:** BTS — 2.77 billion monthly listeners
- **Top Regional Markets by Streams:** Sweden (93.4B), South Korea (87.6B), and South Africa (87.4B)
- **Lowest Reported Genre Skip Rates:** Indie (18.29%) and K-pop (19.11%)
- **Platform Volume Split:** Premium 50.51% vs. Free 49.49%

---

## 🎯 Project Objectives

- Compare artists by total streams and listener reach.
- Explore regional differences in streaming activity.
- Analyze genre-level listening patterns and skip rates.
- Compare Free and Premium platform usage.
- Investigate relationships between streams, listening duration, release year, and other available attributes.
- Translate analytical findings into data-informed business recommendations.

---

## 🛠️ Tech Stack & Tools

- **Environment:** Google Colab / Jupyter Notebook
- **Programming Language:** Python
- **Data Wrangling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Analysis:** Exploratory Data Analysis (EDA), descriptive statistics, aggregation, comparative analysis, and correlation analysis
- **Dataset:** `Spotify_2024_Global_Streaming_Data.csv` — reported as 500 records and 12 attributes

---

## 📈 Analysis & Visualizations

- Artist rankings by streams and monthly listeners
- Regional streaming-volume comparisons
- Genre-level streaming distribution and skip-rate analysis
- Free-versus-Premium platform comparisons
- Skip rate versus listening duration
- Streaming trends by release year
- Average listening duration by genre
- Correlation heatmap of numerical variables

Explore the `charts/` directory for the generated visualizations.

---

## 💡 Strategic Business Recommendations

1. **Promote Engaging Genres:** Test greater editorial visibility for genres with lower observed skip rates, including Indie and K-pop.
2. **Localize Regional Campaigns:** Use market-level streaming patterns to guide regional promotions and content discovery.
3. **Evaluate Premium Conversion Strategies:** Test messaging around subscription benefits and measure actual conversion outcomes.
4. **Improve Music Discovery:** Use artist, genre, and listening-behavior insights to inform playlist and recommendation experiments.
5. **Measure More Than Stream Volume:** Combine streaming totals with listener reach, skip rates, and listening duration for a more balanced performance assessment.

---

## 📁 Repository Structure

```text
spotify-listener-analysis-2024/
│
├── Spotify_Listeners_Analysis.ipynb
├── Spotify_2024_Cleaned.csv
├── spotify-analysis.html
├── README.md
└── charts/
    ├── chart_1_top10_artists_streams.png
    ├── chart_2_top10_artists_listeners.png
    ├── chart_3_top10_countries_streams.png
    ├── chart_4_top10_countries_listeners.png
    ├── chart_5_genre_streams_distribution.png
    ├── chart_6_genre_skip_rate_comparison.png
    ├── chart_7_free_vs_premium_streams.png
    ├── chart_8_skip_rate_vs_duration_scatter.png
    ├── chart_9_streams_30days_vs_total.png
    ├── chart_10_release_year_trends.png
    ├── chart_11_avg_duration_by_genre.png
    └── chart_12_correlation_heatmap.png
```

---

## 🚀 How to Run the Project

1. Clone or download the repository.
2. Open `Spotify_Listeners_Analysis.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure the dataset is available at the location expected by the notebook.
4. Run the notebook cells in sequence to reproduce the analysis.

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## ⚠️ Notes & Limitations

- Findings depend on the dataset's coverage, definitions, and data quality.
- Observed associations do not establish causation.
- Business recommendations should be validated using additional data or experiments.
- Verify all reported metrics against the notebook and source dataset before presenting them as final results.

---

## 👨‍💻 Author

**Darshan Jain**

GitHub: [@darshanmljain](https://github.com/darshanmljain)
