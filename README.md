# Projeto Monitorando

## Description
Projeto Monitorando is a Django-based web application designed to manage mentorados and their tasks. The application allows users to register, log in, and manage their mentorados, schedule meetings, and track tasks effectively.

## Features
- User registration and authentication
- Manage mentorados with detailed information
- Schedule and manage meetings
- Upload videos related to mentorados
- Task management with completion tracking
- Responsive design using Tailwind CSS

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/brunoplatcheck/Projeto_mentorado.git
   cd Projeto_mentorado
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

5. Apply migrations:
   ```bash
   python manage.py migrate
   ```

6. Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```

7. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage
- Access the application at `http://127.0.0.1:8000/`.
- Register a new user or log in with existing credentials.
- Navigate through the application to manage mentorados, schedule meetings, and track tasks.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.

## Links
- GitHub Repository: [Projeto Monitorando](https://github.com/brunoplatcheck/Projeto_mentorado.git)
#
