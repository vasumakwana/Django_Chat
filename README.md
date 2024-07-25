# Django Chat Application

## Overview

Welcome to the Django Chat Application! This is a simple, real-time chat application built with Django. Users can create an account, join chat rooms, and engage in conversations with others.

[![cd Screenshots/Screenshot.png]

## Libraries and Frameworks

The following libraries and frameworks are used to build this chat application:

- **Django** == 3.0.2
- **django-environ** == 4.1.4
- **channels** == 3.0.4

## Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- virtualenv

### Installation

1. **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd Django_Chat
    ```

2. **Activate the virtual environment:**

    ```bash
    virtualenv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install project dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply the migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Run the server:**

    ```bash
    python manage.py runserver
    ```

## Usage

Once the server is running, open your browser and navigate to `http://127.0.0.1:8000/` to start using the chat application.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
