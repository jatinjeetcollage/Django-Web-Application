# Enhanced CRUD Application with Django, JavaScript, and Ajax

This Django web application demonstrates an enhanced CRUD (Create, Read, Update, Delete) system using JavaScript and Ajax. The project integrates Bootstrap 5 to improve UI components like modals and carousels, offering an improved user experience. The application is designed to teach developers how to effectively combine Django with frontend technologies to create dynamic and responsive web applications.

## Features

- **CRUD Operations**: Complete Create, Read, Update, and Delete functionalities implemented with Django and Ajax for seamless user experience.
- **Dynamic Content**: Use of vanilla JavaScript to manipulate DOM elements without reloading the page.
- **Bootstrap 5 UI**: Integration of Bootstrap 5 for responsive and modern UI components.
- **Custom Decorators**: Implementation of custom decorators in Django to enhance functionality.
- **File Upload**: Added Dropzone JS for drag-and-drop file uploads.
- **Loading Spinners**: Enhanced UX with Ajax loading spinners.

## Getting Started

### Prerequisites

- Python 3.x
- Django
- Node.js and npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jatinjeetcollage/Django-Web-Application.git

2. Navigate to the project directory:
bash
cd your-repository
3. Install the required packages:
bash
pip install -r requirements.txt
4. Run the migrations:
bash
python manage.py migrate
5. Start the development server:
bash
python manage.py runserver
Setting up the Frontend
Install the necessary Node packages:
bash
npm install
Compile the static files:
bash
npm run build
Usage
Navigate to http://localhost:8000 in your web browser to view and interact with the application. Use the web interface to perform CRUD operations, which will reflect immediately due to the Ajax integration.
