# 🎧 Spotify Top 50 Global - Power BI Dashboard

This repository features a comprehensive **Power BI Dashboard** designed to analyze and visualize the trends of the Spotify Top 50 Global charts. Using a rich dataset of song metadata, the dashboard provides deep insights into music popularity, artist dominance, and track characteristics.

## 📊 Project Overview
The dashboard serves as a visual exploration of what makes a song "top the charts." It tracks key performance metrics and allows users to filter through global music trends from May 2023 through late 2024.

### 🔑 Key Visualizations & Features
* **Artist Popularity Analysis:** Tracks the most popular artists based on Spotify's popularity score (ranging up to 100).
* **Release Date Trends:** Analyzes the distribution of top songs based on their release dates, showing a mix of modern hits (e.g., *Espresso* by Sabrina Carpenter) and timeless classics (e.g., *Numb* by Linkin Park).
* **Explicit Content Breakdown:** A toggle or chart to differentiate between explicit and clean versions of top-charting tracks.
* **Album vs. Single Insights:** Visualizes whether "Singles" or full "Albums" are more prevalent in the global top 50.
* **Custom Spotify UI:** The dashboard utilizes custom branded assets including icons like `trending.png` and `voice-recording.png` to mimic the actual Spotify user experience.

---

## 🛠️ Tech Stack
* **Visualization:** Power BI Desktop (`Spotify.pbix`)
* **Data Source:** CSV (`top-50-world.csv`)
* **Design Assets:** Custom JPEG/PNG backgrounds and icons for a high-fidelity UI.

---

## 📂 Data Dictionary
The underlying dataset (`top-50-world.csv`) includes the following fields:
* **date:** The chart date.
* **position:** Daily rank on the global top 50.
* **song / artist:** Track details.
* **popularity:** Spotify metric from 0-100.
* **duration_ms:** Length of the track in milliseconds.
* **is_explicit:** Boolean flag for explicit content.
* **total_tracks:** Number of tracks in the associated album.

---

## 🚀 How to Use
1.  **Clone the Repo:** `git clone https://github.com/your-username/spotify-dashboard.git`
2.  **Open Power BI:** Launch the `Spotify.pbix` file using Power BI Desktop.
3.  **Interact:** Use the slicers to filter by artist, date, or explicit content.

---

## 📈 Insights from the Data
* **Top Performer:** Tracks like *un x100to* (Bad Bunny) and *Espresso* (Sabrina Carpenter) reached peak popularity scores of 100 during the tracked period.
* **Longevity:** Identifies "sticky" songs that maintain a position in the top 10 over several months.
