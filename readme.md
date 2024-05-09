# Flask Project Creator

## Short Description
Flask Project Creator: A CLI tool for quickly setting up Flask web applications.

## Long Description
Flask Project Creator is a command-line interface (CLI) tool designed to expedite the creation of Flask web applications. With just a single command, this tool automates the generation of a Flask project directory structure, including essential files and folders such as `run.py`, `__init__.py`, `templates`, and `static`. Additionally, it provides basic templates (`base.html` and `home.html`) along with example route definitions to jumpstart your development process.

This tool leverages Click, a Python package for creating command-line interfaces, to offer a user-friendly experience with customizable options. Whether you're starting a new web project, prototyping ideas, or simply looking to streamline your Flask development workflow, Flask Project Creator simplifies the initial setup process, allowing you to focus on building your application logic without the hassle of manual configuration.

Key Features:
- Automated generation of Flask project directory structure.
- Includes basic templates and example route definitions.
- Customizable options via Click command-line interface.
- Simplifies Flask development workflow, saving time and effort.

CLI Command:
- Command Name: create-flask-project

## Installation

### Prerequisites
- Python 3.x installed on your system
- pip package manager

### Steps
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ImOmkar/flask_project_creator.git
   ```

## Project Structure

The project structure consists of the following components:

- `project_name/`: The root directory of the Flask project.
- `apps/`: Directory containing application modules and templates.
  - `templates/`: Directory for HTML templates.
    - `base.html`: Base template for HTML pages.
    - `home.html`: Example home page template.
  - `static/`: Directory for static files such as CSS, JavaScript, and images.
  - `__init__.py`: Initialization file for the Flask application.
  - `models.py`: File containing data models for the application.
  - `forms.py`: File containing form definitions and validations.
  - `routes.py`: File containing route definitions for the application.
  - `auth_routes.py`: File containing authentication route definitions (if applicable).
- `run.py`: Script to run the Flask application.
- `requirements.txt`: File listing dependencies required by the project.
- `readme.md`: Project documentation file (this file).
- `.env`: File for storing environment variables.

Feel free to customize the project structure further to match your specific project requirements. Once you've made the necessary adjustments, save the changes to the `README.md` file.

