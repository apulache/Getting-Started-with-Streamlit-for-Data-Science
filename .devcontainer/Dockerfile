FROM mcr.microsoft.com/devcontainers/python:0-3.10

COPY ./requirements.txt /setup_ini/requirements.txt

WORKDIR /setup_ini/

RUN pip install --upgrade pip && pip install -r requirements.txt