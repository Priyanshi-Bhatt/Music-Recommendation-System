

---

# 🎵 Music Recommendation System

This project is a **Music Recommendation System** built with **Streamlit**, **Spotipy**, and **machine learning** techniques. It allows users to input their favorite song and get personalized music recommendations based on song similarity and album aesthetics.

## 🛠️ Features
- **User-Friendly Interface**: Interactive web app powered by Streamlit.
- **Music Recommendations**: Suggests top 5 similar songs based on a selected track.
- **Album Art Retrieval**: Fetches album cover images using Spotify API.
- **Custom Background**: Visually appealing UI with an aesthetic background design.

## 💻 Technologies Used
- **Streamlit**: For creating the interactive web interface.
- **Spotipy**: Spotify API integration for fetching track details and album covers.
- **Pickle**: Pre-trained similarity model and dataset management.
- **Python**: Core programming language for development.

## 🚀 How It Works
1. **Song Input**: Select a song from the dropdown menu.
2. **Generate Recommendations**: Click the "Show Recommendation" button to see five similar tracks.
3. **Visual Appeal**: Album art and song names are displayed in a grid format.

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Priyanshi-Bhatt/music-recommendation-system.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```

## 🔗 Spotify Integration
The project uses the Spotify API to fetch album covers. Replace the `CLIENT_ID` and `CLIENT_SECRET` with your own credentials from the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).


---

