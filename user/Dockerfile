FROM python:3-alpine

RUN mkdir /app
COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt
ENV FLASK_APP server.py

CMD ["flask", "run", "--host", "192.34.58.155", "--port", "5000", "--with-threads"]