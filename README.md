# Fibre-Uptake-Rate-Model

## Project description

The project is about developing an application that predicts the uptake rate of fibre in a given geographic location within South Africa. This helps Telcos to decide where to roll out fibre, not primarily on the cost component of the rollout, but based on potential revenues and ROI.
The outcome of this project is an interactive web application that visualizies the predicted fiber-optics uptake rate for geographic locations in South Africa. 

## Environment

The libraries used to set up an environment for this project are pytest, numpy, pandas, matplotlib, seaborn, streamlit, streamlit_folium, and
boto3.

### Setup - you only need to do this once

```bash
# make sure your pip in your base Python installation is up-to-date
python3 -m pip install -U pip
# install the virtualenv package
python3 -m pip install virtualenv
```

### Create the virtual environment - also typically only run when needed

```bash
# create a virtual environment in this directory called '.venv'
python3 -m venv .venv
# You should now see the folder `.venv` in your repo
```

### Activate the virtual environment in a terminal and install the project dependencies

```bash
# Activate the virtual environment
source .venv/bin/activate
# install the requirements for this project
pip install -r requirements.txt
```


## Project Organisation

```ascii

|
├── README.md          <- The top-level README for developers using this project.
│
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering), and a
│                         short `-` delimited description, e.g. `1.0-initial-data-exploration`.
|                       
│
├── requirements.txt   <- The requirements file for reproducing the environment.
```
