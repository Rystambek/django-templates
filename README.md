# django-templates

## Steps

1. git fork
2. git clone
3. cd repo_name
4. create vertual environment
    ```python -m venv venv```
5. activate env
    ```source venv/Scripts/activate```
6. install requirements
    ```pip install -r requirements.txt```
7. create django project
    ```django-admin startproject core .```
8. create django app
    ```python manage.py startapp api```
9. add app to core.settings
    ```python
    INSTALLED_APPS += 'api'
    ```
