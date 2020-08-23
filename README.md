### flask-starter
A boiler plate project for a dockerized flask app with nginx and uWSGI

## Local Environment for Flask

1. setup a venv:
	```
	python -m venv env
	```
2. Run the venv
	```
	source env/bin/activate
	```
3. install requirements
	```
	pip3 install requirements.txt
	```

4. Running Flask App:
	```
	export FLASK_APP=run.py
	export FLASK_ENV=development
	
	flask run
	```
5. Head to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to view the application. 

 
## Docker instructions:
1. Each service goes in its own folder. 
2. Each of these folder needs to have a Dockerfile. 
3.  To run, use the following command and head to localhost.
	```
	docker-compose up --build
	```		


