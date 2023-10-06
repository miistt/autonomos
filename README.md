# autonomos
#comandos
python -m django startproject autonomos
cd .\autonomos\
python manage.py start appsite
python manage.py makemigrations 
python manage.py migrate 
python manage.py createsuperuser
---
