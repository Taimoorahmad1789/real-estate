# RealEstatePro

RealEstatePro is a Streamlit-based real estate intelligence application for the Islamabad market. It combines machine learning price prediction, interactive analytics, and similarity-based property recommendations in a single dashboard.

## Key Capabilities
- **Property price prediction** using a trained ML pipeline
- **Market analytics** with geospatial and distribution visualizations
- **Feature word cloud analysis** by location
- **Smart property recommendations** using precomputed similarity matrices

## Tech Stack
- Python
- Streamlit
- Pandas & NumPy
- Plotly, Matplotlib, Seaborn
- Scikit-learn

## Repository Structure
- `Home.py` - Main Streamlit application
- `requirements.txt` - Python dependencies
- `df (1).pkl` - Base dataset for prediction inputs
- `pipeline (1).pkl` - Trained prediction pipeline
- `data_viz1.xls` - Dataset used for analytics visualizations
- `wordcloud_df.xls` - Features dataset for word cloud generation
- `feature_text.pkl` - Preprocessed feature text for word cloud
- `location_distance.pkl` - Location distance matrix for recommendation search
- `cosine_sim1`, `cosine_sim2`, `cosine_sim3` - Similarity components for recommendations

## Setup
1. Create and activate a Python virtual environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start the app:
   ```bash
   streamlit run Home.py
   ```

## Notes
- Keep all listed data/model artifacts in the project root.
- If optional analytics or recommendation files are missing, the app will display warnings for those sections.

## License
This project currently does not declare a license.
