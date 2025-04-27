# Usage

Create your virtual environment
`py -3.11 -m venv .venv`

Warning! Do not use the following:
`python3.11 -m venv .venv`
as it will create Unix environment and some deps won't work.

Activate the virtual environment
`source .venv/Scripts/activate`

Then
`pip install -r requirements.txt`

# First time setup

Create your virtual environment
`python3.11 -m venv .venv`

Activate the virtual environment
`source .venv/bin/activate` 
or
`source .venv/Scripts/activate`

Install nltk
`pip install nltk`

http://morfeusz.sgjp.pl/
- Windows
- Binding dla Pythona 3.11
- Python 3
(`pip install http://download.sgjp.pl/morfeusz/20250316/Windows/64/morfeusz2-1.99.10-20250316-cp311-cp311-win_amd64.whl`)

Jupyter
`text_mining.ipynb`

`Python: Select interpreter` - select venv
& `Install interpreter` (in Jupyter file after running a cell)
& Install smh like epykernel

After installing, freeze deps
`pip freeze > requirements.txt`

After every virtualenv you have to do (in terminal):
$ python
Python 3.11.4 (tags/v3.11.4:d2340ef, Jun  7 2023, 05:45:37) [MSC v.1934 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
- import nltk
- nltk.download('punkt_tab')
- exit()

Without the code would have failed with `LookupError`. So do it and then run all cells and it should work.
