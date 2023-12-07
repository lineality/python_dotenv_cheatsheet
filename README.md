# python_dotenv_cheatsheet



### Create a .env file containing your secrete key/token in this format, with no quotes
```
key_one=YOUR_KEY_STRING
```


## requirements.txt
your requirements.txt will need to include
```
python-dotenv
```
or run:
```
$ python -m pip install python-dotenv
```

## in python code, imports:
```
from dotenv import load_dotenv

# safe environment variables
load_dotenv()
access_key_one = os.getenv('key_one') 
```

