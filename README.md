# Book Recommender System

## Overview

A Flask‑based web application that provides personalized book recommendations. It leverages a pre‑computed similarity matrix and collaborative filtering to suggest books based on user input. The system also offers fast auto‑suggestions for book titles and displays detailed statistics such as vote count and average rating.

## Features
- Search suggestions with instant auto‑completion.
- Recommendation engine powered by a similarity score matrix.
- Fallback recommendations when the target book lacks sufficient data.
- Clean, responsive UI built with HTML templates.
- Fully container‑ready and easy to deploy.

## Prerequisites
- Python 3.9 or newer
- `pip` package manager

## Setup
1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/talhak739/book-recommender-.git
   cd book-recommender-
   ```
2. **Create a virtual environment (recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application
```bash
python app.py
```
The server will start on `http://127.0.0.1:5000/`. Open this URL in a browser to explore the home page, search for books, and view recommendations.

## Project Structure
- `app.py` – Main Flask application.
- `templates/` – HTML templates for the UI.
- `books.pkl`, `popular.pkl`, `pt.pkl`, `similarity_scores.pkl` – Serialized data files used by the recommendation engine.
- `requirements.txt` – Python dependencies.
- `.gitignore` – Excludes unnecessary files from the repository.

## Contributing
Contributions are welcome. Please fork the repository, create a feature branch, and submit a pull request. Ensure that new code follows the existing coding style and that all tests (if any) pass.

## License
This project is provided under the MIT License. See the `LICENSE` file for details.
