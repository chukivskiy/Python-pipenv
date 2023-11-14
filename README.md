# Python-pipenv
1. Download the Project:
   
  Clone or download the repository from GitHub.

2. Install Dependencies:
   
  Ensure you have Python(3.8 version) and pip installed on your computer, else install it
  
  Open the command line and navigate to the project directory.
  
  Install Flask and Waitress using pip commands:
   pip install Flask
   pip install waitress
   
  Open shell
   pipenv shell
   
3. Test the Project:
   
  Run command to start application
   waitress-serve --host=0.0.0.0 --port=5000 lab:app

  Open a web browser and visit http://localhost:5000/api/v1/hello-world-24

4. Shutdown the Application:

  To stop the application, type Ctrl+C in the command line.
