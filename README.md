# Flask Notes Application

This is a simple web application built with Flask that allows users to add and display notes. The application demonstrates basic functionality of a Flask app including handling form submissions and rendering templates.

## Features

- Add a new note
- Display a list of all notes

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6+
- Flask

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/abfaz/Note_Taking_App_1.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Note_Taking_App_1
    ```

3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

5. Install the dependencies:
    ```sh
    pip install Flask
    ```

## Usage

1. Run the Flask application:
    ```sh
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/`.




## Code Overview

### `app.py`

The main Flask application file which handles routing and logic for adding and displaying notes.

### `templates/home.html`

The HTML template for rendering the notes and the form to add new notes.



## License

This project is licensed under the MIT License.


