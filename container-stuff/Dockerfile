FROM python:3.7.3

ENV LANG=C.UTF-8 LC_ALL=C.UTF-8

WORKDIR /app

ADD requirements.txt /app
RUN pip install --no-cache-dir -r requirements.txt

COPY main.py /app

EXPOSE 8080
