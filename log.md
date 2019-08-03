# 100 Days Of Code - Log

### Day 0: 28 July

**Today's Progress**: Built the enviorment to run Django Projects.Started first Django Project.

**Thoughts:** Learnd to install a virtual enviroment(Conda) in Ubutnu and to create, activate and deativate the virtual enviorment.Built the first Django project and studied various files it includes and its funcition.


### Day 1: 03 August

**Today's Progress**: First Django Application with simple view.Solved first Challange to creat new application and new view. Worked on mapping URLs in Django Application between apps and project.

**Thoughts:** Learnd about plugable django application and created one.There are various flies in  a app such as :

__init_.py ,admin.py ,apps.py ,modelspy ,tests.py ,views.py ,Migrations folder.

**Todays errors:** (1)Django 2.0 path error ?: (2_0.W001) has a route that contains '(?P<', begins with a '^', or ends with a '$'

**soloution :** (1) Instead of using 're_path' you can also use ''(empty string) as the first argument of your path().

urlpatterns = [
    path('admin/', admin.site.urls),
    path('',views.index,name='index'),
]

**Link to work:** [Test_App](https://github.com/rakesh-kadam/My_Django_Stuff/tree/master/first_project)



