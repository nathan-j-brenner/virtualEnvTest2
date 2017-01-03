After you clone the repo,

1. `pip install virtual env`
2. `source env/bin/activate`
 - you should see something like `(env)` on the right side of your prompt
3. `pip list`
	- this should show list of 3 items
4. `pip install -r requirements.txt`
5. `pip list`
	- this should show a list of at least 9 things, and prob an error message, don't worry about it 
6. `python app.py`
	- should see `* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)`
	- if you go to [(http://127.0.0.1:5000/)], you should get a 200 response and the browser shoudl just show "Hello World"
7. `deactivate`
	- the `(env)` should disappear from the prompt