Commands for testing the APIs using curl:

1. GET Method:
    curl -i http://localhost:5000/tasks/2

2. POST Method:
    curl -i -H "Content-Type: application/json" -X POST -d "{\"title\":\"abc\"}" 127.0.0.1:5000/tasks

3. PUT Method:
    curl -i -H "Content-Type: application/json" -X PUT -d "{\"done\":true}" http://localhost:5000/tasks/2

4. DELETE Method:
    curl -i -H "Content-Type: application/json" -X DELETE  http://localhost:5000/tasks/2