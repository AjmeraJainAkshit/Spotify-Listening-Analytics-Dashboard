# 🎵 Spotify Listening Analytics Dashboard

An interactive **Power BI dashboard** for analyzing Spotify listening history and uncovering patterns across albums, artists, tracks, listening time, platforms, shuffle behavior, and skipped tracks.

The project is built as a `.pbix` Power BI report and is designed to turn raw Spotify listening-history data into an interactive analytical experience.

---

## 📊 Dashboard Overview

The report contains three main dashboard pages:

### 1. Overview

Provides a high-level summary of listening activity across:

- **Albums**
  - Total albums played
  - Albums played over time
  - Latest-year album performance
  - Year-over-year comparison
  - Weekday vs. weekend distribution
  - Top albums

- **Artists**
  - Number of artists played
  - Artists played over time
  - Latest-year artist performance
  - Year-over-year comparison
  - Weekday vs. weekend distribution
  - Top artists

- **Tracks**
  - Total tracks played
  - Tracks played over time
  - Latest-year track performance
  - Year-over-year comparison
  - Weekday vs. weekend distribution
  - Top tracks

Interactive filters are available for:
- Platform
- Shuffle status
- Skipped status

---

### 2. Listening Patterns

This page focuses on **when and how music is consumed**.

It includes:

- Listening activity by hour and day
- Listening hours vs. days
- Average listening time
- Track frequency
- Relationship between listening time and track frequency
- Filters for platform, year, shuffle status, skipped status, listening-time range, and track-frequency range

This view helps identify recurring listening habits and usage patterns.

---

### 3. Details Dashboard

A detailed exploration page that allows the listening history to be filtered by:

- Year
- Platform
- Shuffle status
- Skipped status

The detailed table provides granular information such as:

- Album
- Artist
- Platform
- Track
- Listening-related details

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX** for calculated measures and KPIs
- **Power Query** for data preparation
- **Spotify listening history data**
- Interactive Power BI visualizations, slicers, cards, charts, and tables

---

## 🗂️ Data Model

The report uses a Spotify listening-history fact table along with supporting tables for calculations and filtering.

Key model components include:

- `spotify_history` — primary listening-history data
- `Date Table` — calendar/date analysis
- `keys` — measures and KPI calculations
- `Listening Time (min)` — listening-time parameter/filter
- `Track Frequency(Para)` — track-frequency parameter/filter

Common fields used throughout the report include:

- `track_name`
- `artist_name`
- `album_name`
- `platform`
- `shuffle`
- `skipped`
- `Hour`
- Date/Year fields

---

## 📈 Key Metrics

The dashboard contains measures for metrics such as:

- Number of albums played
- Number of artists played
- Number of tracks played
- Total albums
- Total artists
- Total tracks
- Latest-year values
- Previous-year values
- Year-over-year KPIs
- Average listening time
- Track frequency

These measures allow the dashboard to provide both historical trends and comparative insights.

---

## 🎯 Project Objectives

The main objectives of this project are to:

1. Analyze personal Spotify listening behavior.
2. Track changes in music consumption over time.
3. Identify frequently played artists, albums, and tracks.
4. Understand listening patterns by hour and day.
5. Compare weekday and weekend listening behavior.
6. Analyze the effect of shuffle and skip behavior.
7. Provide an interactive dashboard for exploratory analysis.

---

## 🚀 How to Use

### Prerequisites

You need:

- **Power BI Desktop**
- Access to the underlying Spotify listening-history data if the report needs to be refreshed.

### Open the Dashboard

1. Clone or download this repository.
2. Open `Spotify.pbix` using Power BI Desktop.
3. If prompted, configure the data source.
4. Refresh the dataset if required.
5. Use the slicers and visual interactions to explore the dashboard.

---

## 📁 Repository Structure

```text
Spotify-PowerBI/
│
├── Spotify.pbix
├── README.md
└── assets/
    └── screenshots/        # Optional dashboard screenshots
```

---

## 🔍 Example Questions the Dashboard Can Answer

- How many unique albums have been played?
- Which artists are listened to most frequently?
- Which tracks are played the most?
- How has listening activity changed over the years?
- When during the day is listening activity highest?
- How does weekday listening compare with weekend listening?
- How much time is spent listening on average?
- Which tracks have high listening frequency?
- How does listening behavior vary by platform?
- How often are songs skipped or played in shuffle mode?

---

## 💡 Insights

The dashboard is designed to make Spotify listening data easier to explore through interactive visual analysis rather than relying on static reports.

Users can combine multiple filters to drill down from an overall listening summary to specific years, platforms, artists, albums, tracks, and listening behaviors.

---

## 📸 Dashboard Preview

Add screenshots of the Power BI report here after publishing the project to GitHub:

```text
assets/screenshots/overview.png
assets/screenshots/listening-patterns.png
assets/screenshots/details-dashboard.png
```

Example Markdown:

```markdown
![Spotify Dashboard Overview](assets/screenshots/overview.png)
```

---

## 📌 Notes

- The `.pbix` file requires Power BI Desktop to open.
- Dashboard results depend on the underlying Spotify listening-history dataset.
- If the source data is not included in the repository, users will need to configure the appropriate data source before refreshing the report.
- The report was created for data visualization and exploratory analytics.

---

## 👤 Author

**Your Name**

If you found this project useful, feel free to ⭐ the repository and connect with me on GitHub.

---

## 📄 License

This project is available for educational and portfolio purposes. Update this section with your preferred license if you plan to distribute the project publicly.
