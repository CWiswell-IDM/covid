# covid
Agent-based highly configurable infectious disease transmission model in Python

Requirements: Ubuntu

- Edit ~/.pip/pip.conf and add:
```
[global]
index-url = https://packages.idmod.org/api/pypi/pypi-production/simple
```
- python3 -m venv covid
- cd covid
- source bin/activate
- python3 -m pip install dtk_generic_intrahost --upgrade
- python3 -m dtk_app.dtk_setup
- python3 transmission_demo.py
