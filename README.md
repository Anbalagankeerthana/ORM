# Ex02 Django ORM Web Application
## Date: 12/04/2025

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM:
![image](https://github.com/user-attachments/assets/3e09191a-0d1f-46b5-8731-22cd8359c201)




## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM:
```
models.py
from django.db import models
from django.contrib import admin
class Bankloan(models.Models):
  date_of_birth=models.Charfield(max_length=50,primary_key="date_of_birth")
  fathers_name=models.Charfield(max_length=70)
  age=models.IntegerField()
  customerid=models.IntegerField()
  accountdetails=models.IntegerField()


class BankloanAdmin(admin.modelAdmin)
list_display=('date_of_birth','fathers_name','age','customerid','accountdetails')

admin.py
from django.contrib import admin
from.models import Bankloan,BankloanAdmin
admin.site register(Bankloan,BankloanAdmin)
```



## OUTPUT:
![image](https://github.com/user-attachments/assets/7d4284e6-4a81-4c11-9b27-e51f73d75b04)


Include the screenshot of your admin page.


## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
