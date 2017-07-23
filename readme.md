---
 destination: app/templates/index.html

 author:
 	- Ciara Chambers
 	- Nino Ninkovic 
 	- The Collective Unconcious 
 
 title: Python's VIRTUAL ENV README AND GUIDE

---



# HOW TO SETUP A NEW PYTHON VIRTUAL ENVIRONME
NT

1. open terminal and ```cd``` to your 	~/CODE/python/ direcotory. 
2. make a new root project directory by typing in 
```python
	mkdir -p my_new_python_project/app

```
3. ```cd``` into the new fold with ```cd ./my_new_python_project```
4. create the virtual environment with 
```python 
	virtualenv -ppython2.7 venv 
	# where -p you specify the python version you want
	# where venv is the name you want to give the virtual instance. this is the artbitrary name I was telling you about earlier. 
	# Last if you dont care about the python version you can just type 

	virtualenv venv 
```

5. last step! we just need to acivate the python instance. we do this with 
```pyhon 
	source ./venv/bin/activate
	# this command sets the python in that venv folder to be the "system" python for as long as you have the terminal window open. once it's closed, you will need to re-activate the virtual python instance when you want to user it again. 

```
###### NOTES
 - I isntalled a helper for you that is suppsoed to acticate the virtual env's for you as soon as you enter the directory.. we'll see. 
 - I dont knwo if you have been using markdown. but you should.a lot of writers are switching to it. For example, this is markdown. very simpe syntax, but it compiles down to html/css and loooks really nice. there is a helper in this subime package that can preview markdown to html.Like this::::: 