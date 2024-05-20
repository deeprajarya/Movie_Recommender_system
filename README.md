# Movie-Recommender-System
A web-based user-item Movie Recommendation Engine using cosine similarity. The recommendation is based on the idea that if a user enters the name of a movie they like, the application will recommend 5 similar movies. The underlying assumption is that if the user enjoyed the movie they entered, they might also enjoy the recommended movies.

## Features
- **User-Friendly Interface**: Select a movie from a list and get recommendations at the click of a button.
- **Cosine Similarity**: Uses cosine similarity to find movies that are similar to the one selected by the user.
- **Movie Posters**: Displays movie posters along with the titles for a better user experience.

## Screenshot
*(Add a screenshot here to showcase the interface and recommendations)*

### Prerequisites
Ensure you have the following installed:
- Python 3.6 or higher
- pip3
- virtualenv

### Steps
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/deeprajarya/Movie-Recommender-System.git
    cd Movie-Recommender-System
    ```

2. **Create and Activate a Virtual Environment**:
    ```sh
    virtualenv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install the Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Application**:
    ```sh
    streamlit run movie_recommend.py
    ```

### Machine Learning Libraries in Python
The project utilizes the following libraries:
- **Numpy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **streamlit**: For web-application.

### Contributing
Contributions are welcome! Please follow these steps to contribute:

### Fork the repository
Create a new branch: git checkout -b feature/your-feature-name.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/your-feature-name.
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

### Feedback
We value your feedback! If you have any suggestions, issues, or improvements, please open an issue on the repository or contact us directly.