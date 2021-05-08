# TimeAnalyzerWebApp

## Setup  
Open terminal, and make a folder for you project.
```bash
cd Documents 
mkdir TimeAnalyzer (you can name this to your liking)
cd TimeAnalyzer
``` 
** Its important to note, that Python should be > Python 3.8.0

We will now create a virtual enviroment. Do this by running in "TimeAnalyzer" folder..
```bash
python -m venv env 
```
We will now clones this repository into your folder. Also run this in "TimeAnalyzer" folder. 
```git
git clone https://github.com/utkarsh06/TimeAnalyzerWebApp.git
```
After this, run this to activate your virtual enviroment.
```bash 
env\Scripts\activate 
```
*For Mac use this to activate your virtual enviroment*

```bash
source env/bin/activate
``` 

Once this is done, we can navigate to the new "TimeAnalyzer" folder that we cloned from GitHub. 
```bash
cd TimeAnalyzer
```
To download all dependencies simply run this. 
```python 
pip3 install -r requirements.txt 
(OR)
pip install -r  requirements.txt
```
We can finally run our local host, by simply typing.
```python 
python manage.py runserver 
(OR)
python3 manage.py runserver
```
Once you do this go to localhost:8000
