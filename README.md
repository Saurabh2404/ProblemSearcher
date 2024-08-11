
# Coding Problem Search Engine

## Overview

Forgot the question name of a particular website? No worries! Go to our website, search for your questions by entering relevant keywords, and hit search. You can also select the platform you want to stick to.

## Usage

**Perform a search:**

1. Enter a query in the search box.
2. Select the website you want to search.
3. The search engine will process the query using the TF-IDF algorithm and display relevant questions as results.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Saurabh2404/ProblemSearcher.git
    

2. **Install dependencies:**

    Make sure you have Beautiful Soup and Selenium installed in your workspace:

    ```bash
    pip install beautifulsoup4
    pip install selenium
    ```

    If you encounter errors after installing the libraries, try:

    ```bash
    pip install --user beautifulsoup4 selenium
    ```

    For global installation:

    ```bash
    pip install --global beautifulsoup4 selenium
    ```

3. **Hosting the backend locally:**

    Navigate to `Website/Backend`:

    ```bash
    cd Website/Backend
    npm install
    node server.js
    ```

4. **Hosting the frontend locally:**

    Navigate to `Website/Frontend/my_app/`:

    ```bash
    cd Website/Frontend/my_app/
    npm install
    npm start
    ```

    The website will be hosted at [http://localhost:3000](http://localhost:3000).

## Contributing

Thank you for considering contributing to the search engine project! Please follow these guidelines:

1. Fork the repository and create a new branch for your contributions.
2. Make your changes, add tests if applicable, and ensure that the code passes all existing tests.
3. Submit a pull request detailing your changes, the motivation behind them, and any relevant information.

---

Feel free to make any additional adjustments or additions as needed!
