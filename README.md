# Movie Recommendation System

## Project Overview
This is a comprehensive movie recommendation system that leverages both collaborative filtering and content-based filtering techniques to provide personalized movie suggestions to users.

## Key Features
- Hybrid recommendation approach using:
  - Collaborative Filtering
  - Content-Based Filtering
- K-Nearest Neighbors (K-NN) Algorithm
- Cosine Similarity for recommendation calculation
- Pickle files for efficient data storage and retrieval
- Streamlit-based web application for interactive recommendations

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Streamlit
- Pickle

## Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Steps
1. Clone the repository

  gh repo clone jaivanapamala/MovieRecommendationSystem


2. Install required dependencies

  pip install -r requirements.txt



## How It Works
The recommendation system combines two primary approaches:
- **Collaborative Filtering**: Recommends movies based on user interaction patterns
- **Content-Based Filtering**: Suggests movies similar to user's previous preferences

### Key Algorithms
- **K-Nearest Neighbors (K-NN)**: Identifies similar movies or users
- **Cosine Similarity**: Measures content similarity between movies

## Running the Application

streamlit run app.py


## Model Persistence
Pickle files are used to:
- Store preprocessed data
- Save trained recommendation models
- Improve application startup performance

## Future Enhancements
- Implement more advanced recommendation algorithms
- Add user authentication
- Expand movie database
- Improve recommendation accuracy

## Contributing
1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature)
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## License
Distributed under the MIT License. See LICENSE for more information.

## Contact
Name - JAI

Project Link: https://github.com/jaivanapamala/MovieRecommendationSystem
