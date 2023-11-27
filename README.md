# basic-flask-demo

post - http://127.0.0.1:5000/tasks 
payload: 
{
  "title": "this is a cool task"
}

put - http://127.0.0.1:5000/tasks/4
payload:
{
	"done": true
}

get - http://127.0.0.1:5000/tasks

delete - http://127.0.0.1:5000/tasks/4
