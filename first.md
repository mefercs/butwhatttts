# This is the first model's that we are gonna create with django

[Instalation tutorial](https://nextgentips.com/2022/01/22/how-to-install-python-django-on-ubuntu-20-04/)

* To activate the current env we use `source projectName/bin/activate` in the terminal where the virtual enviroment is alocated where the virtual enviroment is alocated.
* To deactivate the env we use in shell the next command `deactivate`

To run the current env
`python3 manage.py runserver`


* It is better to put your code in some directory outside of the document root, to prevent the risk that people may be able to view your code over the web.
  - A good directory is /home/mycode.


#### To show off the project on other computers on the newtork use:

```sh
python manage.py runserver 0:8000
```
#### To create an app within a project we'll execute the next command
This command should be stay in the same **manage.py** directory, and within also the project
```sh
python3 manage.py startapp polls
```
