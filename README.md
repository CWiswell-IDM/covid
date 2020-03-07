# Covid-19 Python model
Agent-based highly configurable infectious disease transmission model in Python

## Ubuntu

- Edit ~/.pip/pip.conf and add:
```
[global]
index-url = https://packages.idmod.org/api/pypi/pypi-production/simple
```
- Run:

```
- python3 -m venv covid
- cd covid
- source bin/activate
- python3 -m pip install dtk_generic_intrahost --upgrade
- python3 -m dtk_app.dtk_setup
- python3 transmission_demo.py
```

## Windows

- Run a command prompt (cmd).
- Navigate to a directory you want to work in.
- Run:
```
- pip install dtk_generic_intrahost --index-url https://packages.idmod.org/api/pypi/pypi-production/simple --upgrade --force-reinstall --no-cache-dir
- python -m dtk_app.dtk_setup
- python transmission_demo.py
```

## Configuration
- To learn about how to configure the nd.json (population and vital dynamics): https://quickstart.idmod.org/#PopulationInitialization
- To learn about how to configure the gi.json (disease): https://quickstart.idmod.org/#intrahost
