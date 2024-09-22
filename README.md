# DRF-CRUD
Django Rest Framework Basic CRUD 

- enable virtual environment
- install packages from requirements.txt
- `python3 manage.py runserver` from project directory

### API Endpoints
- [GET] http://locahost/api/users/
- [GET] http://locahost/api/users/`id`
- [POST] http://locahost/api/users/
  Body:
  ```
  {
    "age": 98,
    "name": "Garry"
  }
  ```
- [PUT] http://locahost/api/users/`id`
  ```
  {
    "age": 98,
    "name": "Garry"
  }
  ```
- [DELETE] http://locahost/api/users/`id`

 
