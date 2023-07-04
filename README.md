https://flask.palletsprojects.com/en/2.0.x/tutorial/

Setup to make the project run:

## Initialize DB
```
export FLASK_APP=flaskr
export FLASK_ENV=development
flask init-db
```
There will now be a flaskr.sqlite file in the instance folder in your project.

## Firebase

Installing Firebase CLI:
```
curl -sL https://firebase.tools | bash
```

Open Virtual Desktop in Codio tab

Login to Google account:
```
firebase login
```

Check that log in worked:
```
firebase projects:list
```

Generate CI token:
```
firebase login:ci
```

Save CI token to environment variable:
```
export FIREBASE_TOKEN=string_firebase_generated
```

Initialize Firebase in project:
```
firebase init hosting
```