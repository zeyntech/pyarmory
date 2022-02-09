# pyarmory
Collection of useful Python codes 

### Table of Content
1. Python Virtual Environments


### 1. Python Virtual Environments
Windows Implementation:
1. Create the directory structure for your project. I usually use the following:
	```
	projects
		project_name
			other
			repos
			venvs

	```
1. In the terminal, navigate to the venvs directory
```cd path/to/venvs```
1. Check if the correct python version is installed
```python --version```
1. Check if the correct pip version is installed
```pip --version```
1. Run the following command to create a python virtual env
```python -m venv your_venv_name```
1. Once the environemnt is created and ready, activate it
```source your_venv_name/Scripts/activate```
1. Once the environemnt is activated, install the project requirements
```
cd path/to/requirements_dir
pip install -r requirements.txt
```
1. Once the environemnt is not needed, deactivate it
```
deactivate
```



