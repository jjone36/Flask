# Flask Tutorials
*: This repo contains all the materials for [Flask Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH) of [Corey Schafer](https://www.youtube.com/channel/UCCezIgC97PvUuR4_gbFUs5g) on Youtube*

This tutorial is consist of 13 courses learning how to build a full-feature Flask application for scratch. It covers how to get started with Flask, use templates, create a database, upload pictures, create an authentication system, and much more.

<br>

* **[course_1](https://github.com/jjone36/Flask/tree/master/course_1) :** basic templates, layout and inheritance, block content box, add bootstrap & CSS

* **[course_2](https://github.com/jjone36/Flask/tree/master/course_2) :** create **forms.py** / add register & login forms > make connection with **forms.py** by *'@app.route'* on **hello.py**

* **[course_3](https://github.com/jjone36/Flask/tree/master/course_3) :** install SQLAlchemy database > create db tables *User*, *Post* in **models.py** > separate the flask running part, the app init part, and the routes part from **hello.py** > make linkages between the files by "from *hello* import *(module)*"

  [ run.py >> __init__.py >> routes.py (~~ models.py & forms.py) ]
