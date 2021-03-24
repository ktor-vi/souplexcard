# Souplexcard

Hello and welcome to my TED talk, no I'm joking. 

To RUN this project started by Monty, you will need the following : 

A *NIX (preferably) machine, you can run it on a live usb ith persistence or virtual machine  if you desire to keep Windows somewhere.

- Python3 installed
- Pip3 installed

So, first clone the repo and enter it, then : 

`pip3 install virtualenv` to install beautiful virtual environments 

`virtualenv Django` to create them

`source Django/bin/activate` to activate the the comfy virtual space called Django


enter the Django folder then : `pip3 install -r requirements.txt` to install the dependencies 

```python3 manage.py runserver``` TO START THE WEBSERVER.

#### You will be asked for a .env file, create it in the Splx folder with a *secret*  key

#### You might be asked to perform a migration, just type : `python manage.py migrate`

Go to http://127.0.0.1:8000/ as proposed and you're off !

Welcome to the cuillère code !


#### Saying Goodbye

`deactivate` at the end of your session if you wish to leave Django's *comfycybersofty* space
