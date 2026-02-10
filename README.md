# Python Docker Hello World

Flask web application with optional Docker support.

## Run with Docker

```bash
docker build -t python-hello-world .
docker run -p 5000:5000 python-hello-world
```
Server runs at:
http://localhost:5000

## Run without Docker
```
pip install -r requirements.txt
python app.py
```
