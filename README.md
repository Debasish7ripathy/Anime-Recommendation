# Anime Recommendation System

This is a Flask-based web application that recommends anime based on user input. The recommendations are generated using a pre-trained similarity matrix.

## Features

- **Anime Recommendation**: Users can input the name of an anime and get a list of recommended anime.
- **Autocomplete**: The input field supports autocomplete to help users find the anime they are looking for.
- **Dynamic UI**: The UI is dynamic and responsive, providing a smooth user experience.

## Setup

### Prerequisites

- Python 3.x
- Flask
- Pandas
- Pickle

### Installation

1. **Clone the repository**:

    ```sh
    git clone https://github.com/Debasish7ripathy/Anime-Recommendation.git
    cd Anime-Recommendation
    ```

2. **Install the required packages**:

    ```sh
    pip install flask pandas
    ```

3. **Prepare the data**:

    Ensure you have the `anime.pkl` and `similarity.pkl` files in the root directory of the project. These files contain the anime data and the similarity matrix, respectively.

### Running the Application

1. **Start the Flask server**:

    ```sh
    python app.py
    ```

2. **Access the application**:

    Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

1. **Home Page**:

    - The home page displays an input field where users can enter the name of an anime.
    - The input field supports autocomplete, suggesting anime names as the user types.

2. **Get Recommendations**:

    - Enter the name of an anime and click the "Explore Recommendations" button.
    - The application will display a list of recommended anime along with their posters.

## File Structure

- `app.py`: The main Flask application file.
- `anime.pkl`: Pickle file containing the anime data.
- `similarity.pkl`: Pickle file containing the similarity matrix.
- `templates/index.html`: HTML template for the home page.
- `static/`: Directory for static files (CSS, JavaScript, etc.).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

