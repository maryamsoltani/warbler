## Warbler-app

### Visit on Heroku
1. To access, please visit https://warbler-75.herokuapp.com/
2. create account via sign up button
3. initial "home" will show your profile on the left, to find other users click all users link in nav bar
4. follow any user to see thier warbles appear on your home feed!


### Run locally
To get this application running, make sure you do the following in the Terminal:

1. `python3 -m venv venv`
2. `source venv/bin/activate`
3. `pip install -r requirements.txt`
      -   If you are using Python 3.8 instead of 3.7, then you will have issues with installing some of the packages in the requirements.txt file into your virtual environment.
For Python 3.8 users, we recommend deleting pyscopg2-binary from the requirements.txt file, and using `pip install pyscopg2-binary` in the terminal in order to successfully install this package.
4. `createdb warbler`
5. `python seed.py`
6. `flask run`
