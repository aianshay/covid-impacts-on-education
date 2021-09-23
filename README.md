# Covid Dashboard
Non-obvious impacts of the covid-19 pandemic

## Installation


### Requirements

Use conda to install the requirements with:


```
conda env create -f requirements.yml --name covid-dashboard 
```

Activate the environment

```
conda activate covid-dashboard
```

## Obtaining data

Extract data in the first use

```
make get_data
```

Run the server

```
make run_server 
```
