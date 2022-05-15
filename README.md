<h2>Elon Chatbot Installation</h2>


pre-requirements :
- [python 3.8](https://www.python.org/downloads/release/python-380/)
- [pip](https://www.cours-gratuit.com/tutoriel-python/tutoriel-python-comment-travailler-avec-le-package-pip-en-python) 
- [git](https://www.activestate.com/resources/quick-reads/pip-install-git/)


installation from CMD :



```python
git clone https://github.com/Ashoka74/ElonBot.git
cd ../PATH_TO_FOLDER
python -m pip install -r requirements.txt
```


running :

- replace 'GPT3_API_KEY' by your personal key in views.py file

```python
manage.py runserver
```

- open the link or open http://127.0.0.1:8000/ in your browser
</br>

If you are still unable to run the app, try:

```python
manage.py makemigrations
manage.py migrate
manage.py runserver
```
