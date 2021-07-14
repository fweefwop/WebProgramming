## Day01: Setting up the environment

### Please do the following:

1. Set up an Ubuntu (or your fav. distro of Linux) VM     
2. Learn about python virtualenv and install it with ```sudo apt-get install python3-venv```                 
3. Create a project dir. e.g. "hello". Do the rest in this dir.
4. create a virtual env named venv ```python3 -m venv venv```
5. Activate the vene ```. venv/bin/activate```
6. Install Flask ```pip install Flask```           
[Ref. flask installation](https://flask.palletsprojects.com/en/2.0.x/installation/)                 
                                                
###Test your installation:                             
1. put [hello.py](hello.py) in your project directory               
2. set env ```export FLASK_APP=hello```              
3. run it ```flask run```                
4. Visit the test site  [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
If you  you see "Hello World!" then you're done             
