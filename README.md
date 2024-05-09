
1) When you create a new python project or pulls down a project - you need to install a fresh python environment:

-> python -m venv local_python_environment

------------------------------------------------------------------------------------------------------------------------------

2) Activate that environment using following command in the folder directory

-> .\local_python_environment\Scripts\activate

------------------------------------------------------------------------------------------------------------------------------

3) Install all packages from your requirements.txt using command within you local environment

(local_python_environment) pip install -r requirements.txt

------------------------------------------------------------------------------------------------------------------------------

4) Before pushing to github create a requirements.txt file using 

-> pip freeze > requirements.txt

------------------------------------------------------------------------------------------------------------------------------

5) Also you can keep on updating it along with package installation such as

-> pip install requests && pip freeze > requirements.txt

------------------------------------------------------------------------------------------------------------------------------


