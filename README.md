pre-requirements :
- git
- pip 
- python (3.8 for dependencies)

installation :

$ git clone https://github.com/Ashoka74/ElonBot.git
$ cd ../PATH_TO_FOLDER
$ python -m pip install -r requirements.txt


running :

- replace 'GPT3_API_KEY' by your personal key in views.py file

$ manage.py runserver
$ open the link or open http://127.0.0.1:8000/ in your browser


If you are unable to run the app, try:

manage.py makemigrations
manage.py migrate
manage.py runserver
