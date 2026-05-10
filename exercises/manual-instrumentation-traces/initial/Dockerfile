FROM docker.io/python:3-slim

WORKDIR /src/app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY src/ .

CMD ["python", "app.py"]
