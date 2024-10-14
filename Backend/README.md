Install Requirements:
    Make sure you are currently in the 'Backend' directory
    Type cmd 'pip install -r requirements.txt' to install the necessary requirements for the project
    Highly recommended to do this within a virtual environment

Make and use Virtual Environment(VENV):
    In the desired directory type cmd 'python -m venv {nameOfVirtualEnvironment}'
    For Windows users:
        Type cmd 'cd env/Scripts/' then type cmd './activate'
    For Linux users:
        Type cmd 'source env/Scripts/activate'
    This will create and activate a virtual environment, allowing you to keep dependecies seperate.

Environment Variables:
    Using the dotenv package to handle the loading and storing of environment variables
    To get started:
        In the Backend/DjangoBackend directory make a file called .env
        make a key value pair -> SECRET_KEY = "{secret key}".
        This will then be loaded into the environment during startup
        from where we can call it using os.getenv("SECRET_KEY")
    Key-Value pairs are used to store the environment variables.
    Doing this helps keep certain aspects of the project safe.
    For more information visit the dotenv docs -> https://pypi.org/project/python-dotenv/
        
