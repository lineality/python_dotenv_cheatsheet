# python_dotenv_cheatsheet

## requirements.txt
your requirements.txt will need to include
```
python-dotenv
```
or run:
```
$ python -m pip install python-dotenv
```

# pip install python-dotenv
from dotenv import load_dotenv

# safe environment variables
load_dotenv()
access_key_one = os.getenv('key_one') 


### Create a .env file containing this text, with no quotes
```
key_one=YOUR_KEY_STRING
```
