# 100 Days Of Code - Log

### Day 0: 28 July

**Today's Progress**: Built the enviorment to run Django Projects.Started first Django Project.

**Thoughts:** Learnd to install a virtual enviroment(Conda) in Ubutnu and to create, activate and deativate the virtual enviorment.Built the first Django project and studied various files it includes and its funcition.


### Day 1: 03 August

**Today's Progress**: First Django Application with simple view.

**Thoughts:** Learnd about plugable django application and created one.There are various flies in  a app such as :
#__init_.py - Its a script that lets python know that this directory can be treated as a package.
#admin.py - Register models which Django will use them with Django admin interface.
#apps.py - Here you can place application specific configuration
#modelspy - Here you store the applications data models
#tests.py - Here you can store test functions to test your code
#views.py - Here you have functions that handle request and return responses
#Migrations folder - This directory stores database specific information as it relates to the models

Todays errors: (1)Django 2.0 path error ?: (2_0.W001) has a route that contains '(?P<', begins with a '^', or ends with a '$'
soloution : (1) Instead of using 're_path' you can also use ''(empty string) as the first argument of your path().
urlpatterns = [
    path('admin/', admin.site.urls),
    path('',views.index,name='index'),
]




