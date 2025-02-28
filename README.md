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

## install jupyter and make sure pip3 is up to date
```sh
pip3 install jupyter
pip3 install --upgrade pip3
```

## start the notebook server
```sh
jupyter notebook
```

## run the notebook
open the [supplier_due_diligence_with_anthropic jupyter notebook](supplier_due_diligence_with_anthropic.ipynb) via the web console
run individual cells one by one or all cells at once

## stop the notebook
_Ctrl C_

## stop virtual env
```sh
deactivate
```

## troubleshooting
in case there are issues with the virtual env,
deleting `rm -rf .venv` 
and recreating the virtual env `python3 -m venv .venv` may help
