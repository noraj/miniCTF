# MINICTF

### A platform build in django for hosting CTF events. 

#### Live demo 

[https://xyz-minictf.herokuapp.com/](https://xyz-minictf.herokuapp.com/)

#### FEATURES :

* Cool Interface
* Score Board
* Responsive Design
* Password Change Support 
* and a lot more.

#### SCREENSHOTS :

Challenge Page

<img src="readmeimg/challenges.png" width="100%">

Challenge View

<img src="readmeimg/onechallenge.png" width="100%">

Score Board

<img src="readmeimg/scoreboard.png" width="100%">

Team Details

<img src="readmeimg/details.png" width="100%">


#### Test it locally

###### Requirments

```
python 3.5.x
django 2.0
```

###### Install django

```sh
$ sudo pip3 install django
```

<b>Want to make this process fast. Switch to [local branch](https://github.com/DivyanshuSahu/miniCTF/tree/local)</b>

###### Install miniCTF

```sh
$ git clone https://github.com/DivyanshuSahu/miniCTF.git
$ django-admin startproject minictf
copy all files and folders from git clone folder(miniCTF) to django project folder(minictf), then
$ python manage.py makemigrations accounts challenges
$ python manage.py migrate
$ python manage.py runserver
```

Then register or create superuser and add challenges.
