# Flask Todo App

This is a simple Todo application built using Flask and SQLAlchemy. The app allows users to create, read, update, and delete (CRUD) todo items. It also includes a navigation bar for easy navigation.

## Features

- Add new todo items with a title and description.
- View a list of all todo items.
- Update existing todo items.
- Delete todo items.
- Responsive design using Bootstrap.

## Prerequisites

- Python 3.x
- Flask
- Flask-SQLAlchemy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flask-todo-app.git
   cd flask-todo-app
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://127.0.0.1:5000`.

## File Structure

- `app.py`: Main application file containing routes and logic.
- `templates/`: Contains HTML templates (`base.html`, `index.html`, `update.html`).
- `todo.db`: SQLite database file (auto-generated).

## Usage

- Navigate to the homepage to view all todos.
- Use the form to add new todos.
- Click the "Update" button to edit a todo.
- Click the "Delete" button to remove a todo.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.