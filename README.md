# Speech Emotion Recognition

create virtual environment:
* py -m pip install --user virtualenv
* py -m venv env

Note: You should exclude your virtual environment directory from 
your version control system using .gitignore or similar.

Activating a virtual environment:
* .\env\Scripts\activate

confirm virtual environment by location of Python:
* .../env/bin/python.exe

* where python

Leaving the virtual environment:
* deactivate

Installing specific versions:
* pip install requests==2.18.4
* pip install requests>=2.0.0,<3.0.0

Installing from source:
* cd google-auth
* pip install .

Freezing dependencies:
Pip can export a list of all installed packages and their versions using the freeze command
* pip freeze