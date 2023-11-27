# basic-flask-demo

pip3 install flask
python main.py

post - http://127.0.0.1:5000/tasks 
<br /><br />
payload: 
{
  "title": "this is a cool task"
}

put - http://127.0.0.1:5000/tasks/4
<br /><br />
payload:
{
	"done": true
}

get - http://127.0.0.1:5000/tasks

delete - http://127.0.0.1:5000/tasks/4
