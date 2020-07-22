# Flask_TODO

Welcome to the TODO List Maker using the Flask Framework of Python 

Do run this file in the Virtual Environment as it does not affect the local files
<h2>Step-1</h2>
Activalte the Virtual Environment

1.pip install virtualenv
2.virtualenv env
3.env\Scrips\activate.bat

<h2>Step-2</h2>
Now install the required fields 

1 - pip install flask flask-sqlalchemy

<h2>Step-3</h2>
Now Create your DB by going into the python shell

1.python
2.from app import db
3.db.create_all()
#hey your almost done at your project and ready to boom
4.exit()   #Coming out of the pythin shell

<h2>Step-4</h2>
Noww run the Main app.py

1.py app.py 

something like this would show up in your CMD

(env) C:\Users\vishnu\Desktop\FLASK_FC>py app.py
C:\Users\vishnu\Desktop\FLASK_FC\env\lib\site-packages\flask_sqlalchemy\__init__.py:834: FSADeprecationWarning: SQLALCHEMY_TRACK_MODIFICATIONS adds significant overhead and will be disabled by default in the future.  Set it to True or False to suppress this warning.
  'SQLALCHEMY_TRACK_MODIFICATIONS adds significant overhead and '
 * Serving Flask app "app" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Restarting with stat
C:\Users\vishnu\Desktop\FLASK_FC\env\lib\site-packages\flask_sqlalchemy\__init__.py:834: FSADeprecationWarning: SQLALCHEMY_TRACK_MODIFICATIONS adds significant overhead and will be disabled by default in the future.  Set it to True or False to suppress this warning.
  'SQLALCHEMY_TRACK_MODIFICATIONS adds significant overhead and '
 * Debugger is active!
 * Debugger PIN: 800-977-780
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 
 
 <h1>Finally Done</h1>
 
 Now your are all set up and running a basic TODO Manager using the Flask and DB
 
 
 <h3>Thanks For Coiming and checking the File</h3>


