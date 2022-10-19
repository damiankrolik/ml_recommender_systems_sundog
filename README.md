# ml_recommender_systems_sundog

## wsl first run

`git clone git@github.com:user-gut/ml_recommender_systems_sundog.git`

'''git config user.email "damian.krolik+user-gut@gmail.com"
git config user.name "damian.krolik"'''

## windows trying to use conda

firtst run - in cmd.exe or code terminal:
activate conda enviroment:

`activate RecSys`

`cd \ml_recommender_systems_sundog\GettingStarted`
`python ./GettingStarted.py`

if You dont use **./** you will encoutner error:

```
   data = ml.loadMovieLensLatestSmall()
  File "F:\Github\ml_recommender_systems_sundog\GettingStarted\MovieLens.py", line 22, in loadMovieLensLatestSmall
    os.chdir(os.path.dirname(sys.argv[0]))
OSError: [WinError 123] Nazwa pliku, nazwa katalogu lub składnia etykiety woluminu jest niepoprawna: ''
```

## instalacja venv numpy i surprise w10 - not fu

`virtualenv venv`

w10 venv activation:
`venv\Scripts\activate.bat`
wsl activate:
`source venv/bin/activate`

`pip install numpy`
`pip install scikit-surprise`

wsl vscode ask for ipykernal install while trying to run in ipynb - jupyter notebok page:
`!python ./TestMetrics.py` 

`pip install ipykernel`

