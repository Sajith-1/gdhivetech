# HivetechWear
HivetechWear
![Screenshot 2023-02-28 at 12 57 12 PM](https://user-images.githubusercontent.com/112057794/221783529-bd5fcb49-dfc9-4ab6-b0ff-716ce0beb347.png)


Hive-Techwear-GD
Hive Tech Wear in React & Redux + Django
Hive Tech Wear, with a frontend built in React & Redux and a backend built in Django API.
Live Demo
This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.

Check out FRONTEND LIVE DEMO here!! (https://hivetechfront.sajith-1.repl.co/)

Check out API LIVE DEMO here!! (https://backhive.sajith-1.repl.co/)

Tech used
* Frontend : React & Redux
* Backend : Django
How to Install
Git Clone
git clone
Backend setting
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
Frontend setting
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
