About
An aid for all aspects of the Vulnerability Management Lifecycle

Build an Asset Inventory
Automatically updates Vulnerability Threat Intelligence with latest NVD records
Find Vulnerable Assets automatically through CPE URI System
Prioritize efforts through Risk Framework Integration
Assist Patch Managment processes and timelines with Ticketing System
Evolve Processes and SLA by tracking Metrics and Compliance
Accelerate your Organistational Security Posture and Maturity.


Requirements
Python 3+
Node.js
Windows, macOS, Linux/Unix, Solaris
Celery
Message Broker Software

Features
User Administation
Threat Intelligence
Patch Management
Vulnerability Discovery
Vulnerability Management Metrics
Risk Framework Integration
Asset Management

Django
Install Virtual Environments: pip install virtualenv
Create your Virtual Environment. Name does not matter: virtualenv “name as you like”
Install Django: pip install Django
Install Project Dependencies: pip install -r requirement.txt
Navigate to the project file “settings.py” and update the database settings depending on the technology and credentials you are using. MySQL Example below:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'vuln_database',
        'USER': 'vuln_user',
        'PASSWORD': '******',
        'HOST': 'localhost',
        'PORT': '',
    }
Navigate to folder with manage.py in CLI and run commands: 
$ python manage.py makemigrations
$ python manage.py migrate
Create a superuser to log in to the application: python manage.py createsuperuser
Start the server: python manage.py runserver 8080
Angular
Install Node.js: Source
Run this command: npm install
Navigate to Angular project folder in CLI and run the command: ng serve --port 8081
Use a browser of your choice to access the application at http://localhost:8081/login and login with the Superuser you created
