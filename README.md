# Unemployment-MW



## Setup

API Key 
Obtain an AlphaVantage API Key. A normal key should be fine, but alternatively you can use one of the prof's "premium" keys. 

Create a virtual enviornment 

```sh 
conda create -n unemployment-env python=3.10
```

```sh 
conda create -n unemployment-env 
```

Install some third party packagaes:

```sh
pip install -r requirements.txt
```

## Usage

Run the report: 

```sh
python app/unemployment.py

python -m app.unemployment
```

Run the web app: 

# Mac OS:
FLASK_APP=web_app flask run

# Windows OS:
# ... if `export` doesn't work for you, try `set` instead
# ... or try a ".env" file approach
export FLASK_APP=web_app
flask run

## Testing

Run tests:

```sh
pytest
```