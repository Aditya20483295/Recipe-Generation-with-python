# Recipe Generator App

## Overview

The Recipe Generator App is a web application built with Streamlit that allows users to explore and generate recipes based on their preferences. Users can register, log in, filter recipes by cuisine, diet, and cooking time, and view their recipe history. The application utilizes a SQLite database for user management and recipe storage.

## Features

- **User  Registration and Login**: Secure user authentication with hashed passwords.
- **Recipe Generation**: Generate random recipes based on user-defined filters such as cuisine, diet, maximum cooking time, and ingredient search.
- **Recipe History**: View a history of previously generated recipes.
- **Responsive Design**: User-friendly interface with sidebar navigation for easy access to features.

## Technologies Used

- Python
- Streamlit
- Pandas
- SQLite
- hashlib
- datetime

## Getting Started

### Prerequisites

Make sure you have Python installed on your machine. You will also need to install the required libraries. You can do this using pip:

```bash
pip install streamlit pandas
