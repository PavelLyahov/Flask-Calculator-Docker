# Flask-Calculator-Beginner
This is Beginners Friendly Flask Application which does the basic arithmetic operations (+,-,*,/) 

[Click here check the Docker Hub Repo](https://hub.docker.com/r/santhoshkdhana/flask-calculator-beginner)

py -m venv <venv> - <name of virtual variable>
pip install flask - load flask framework
venv\Script\activate - activate script ???
flask run OR   py app.py

go to dir with project
docker image build -t <cmd> . - <name of image>
docker run -p 5000:5000 -d <cmd>

Run test case
docker run -it flask-hello-world pytest test.py

docker login
docker push cmd liakhaupavel/cmd


**API**

POST - /add

POST - /subtract

POST- /multiply

POST- /division

send POST request to the endpoints with a JSON in the body

x is the first variable

y is the second variable

Sample JSON:
```JSON
{
    "x":193,
    "y":657
}
```
Sample Response:
```JSON
{
    "Message": -464,
    "Status Code": 200
}
```
