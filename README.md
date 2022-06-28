## Warbler-app
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

![Alt text](https://github.com/maryamsoltani/warbler/blob/main/warbler.gif)
<br>
<img src="https://github.com/maryamsoltani/warbler/blob/main/warbler.gif" width= "40" height = "40" />



Running Tests
-------------
1. `python3 -m venv venv`
2. `source venv/bin/activate`
3. `pip install -r requirements.txt`
4. `createdb warbler`
5. `python -m unittest test_message_model.py`

