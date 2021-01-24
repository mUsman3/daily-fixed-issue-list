FROM python:3

ENV PYTHONUNBUFFERED 1

WORKDIR /app

ADD . /app

COPY ./req.txt /app/req.txt

RUN pip install -r req.txt

COPY . /app
