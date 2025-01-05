# AI powered Supplier Due Diligence

## precondition
_python3_ and _pip3_ installed

## create virtual env
```sh
python3 -m venv .venv
```

## start virtual env

```sh
source .venv/bin/activate
```

## install jupyter 
```sh
pip3 install jupyter
```

## start the notebook server
```sh
jupyter notebook
```

## start and run the notebook
open the [supplier_due_diligence_with_anthropic jupyter notebook](supplier_due_diligence_with_anthropic.ipynb) supplier_due_diligence_with_anthropic.ipynb via the web console
run individual cells one by one or all cells in one go

## stop the notebook
_CTRL C_

## stop virtual env
```sh
deactivate
```

## troubleshooting
`rm -rf .venv` - in case there are issues with the virtual env,
this helps including recreating the virtual env `python3 -m venv .venv`