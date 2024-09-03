# RappiPay
## Dependencies
- Django
- MySql

## Dev Commands
```bash
pip install django
pip install virtualenv
pip install mysqlclient
```

## Start
Write the following commands in the terminal to start server.
```bash
cd RappiPay
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
virtualenv rappipayenv
rappipayenv\Scripts\activate
pip install django
cd ..
python manage.py runserver
```

## Exit
```bash
ctrl + c
deactivate