# FLASK
Hi, I'm Arsen, this project is an example of a Flask web application that responds to a request to `/api/v1/hello-world-8` with the text "Hello World 8".

## Installation

Before running the project, you need to install Python 3.10, Poetry and Flask 3.0.0 for dependency management.

### Installation steps

1. **Install Python 3.10**
   - Download and install Python 3.10 from the [official Python site](https://www.python.org/downloads/).

2. **Create a virtual environment**
   - Open a terminal in the project directory.
   - Run the command: `python3.10 -m venv virtual_environment_name`.

3. **Activate the virtual environment**
   - For Windows: `virtual_environment_name\Scripts\activate`.
   - For macOS and Linux: `source virtual_environment_name/bin/activate`.

4. **Install Poetry**
   - Run the command: `pip install poetry`.

5. **Install project dependencies**
   - Execute the command: `poetry install`.
     
## Usage

To run the application, run the following command in the terminal:
```bash
flask run
```
You can now go to http://127.0.0.1:5000/api/v1/hello-world-8 in your web browser to see the response from the server.

## Author
Arsen Dolichnyi 

