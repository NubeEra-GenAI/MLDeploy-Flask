# flask-salary-predictor
This is project predicts the salary of the employee based on the experience.

# Model
model.py trains and saves the model to the disk.
model.pkb the pickle model 

# App
app.py contains all the requiered for flask and to manage APIs.



Procedure--
Open command Prompt and go to given directory and then run python app.py

## Install Tool:
```bash
sudo apt update
sudo apt install python3-pip
apt-get install python3-virtualenv
```

## Check Versions:
```bash
python3 --version
pip --version
pip show virtualenv
```

## Activate Environment:
```bash
virtualenv .env
source .env/bin/activate
```

## Clone Project:
```bash
git clone https://github.com/NubeEra-GenAI/MLDeploy-Flask.git
cd MLDeploy-Flask
```
## Install & Run:
```bash
pip install -r requirements.txt
python model.py
python server.py
python request.py
```
