# 🎬 Movie Recommender System

A content-based movie recommendation system that suggests similar movies based on your preferences.

## 🌟 Features

- Content-based filtering using movie metadata
- Suggests movies based on:
  - Plot overview
  - Cast
  - Genres
  - Keywords
- Clean and intuitive user interface using Streamlit
- Fast recommendations using pre-trained model

## 🛠️ Technologies Used

- Python 3.x
- Streamlit
- scikit-learn
- NLTK
- Pandas
- NumPy

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Movie-Recommender-system.git
cd Movie-Recommender-system
```

2. Create and activate virtual environment:

```bash
python -m venv myfirstproject
source myfirstproject/bin/activate  # Linux/Mac
.\myfirstproject\Scripts\activate   # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Open your browser and go to `http://localhost:8501`
3. Select a movie from the dropdown
4. Get personalized movie recommendations!

## 📝 Dataset

The system uses TMDB movie dataset containing:

- 5000+ movies
- Plot descriptions
- Cast information
- Genre classifications
- Keywords

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
