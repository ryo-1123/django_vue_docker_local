FROM python:3.7

RUN apt-get update -qq

ENV PYTHONUNBUFFERED 1
ENV PYTHONUNBUFFERED 1
ENV PIPENV_VENV_IN_PROJECT 1

RUN mkdir /app

WORKDIR /app

ADD requirements.txt /app/
RUN pip install -r requirements.txt
