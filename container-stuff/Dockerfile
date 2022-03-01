FROM python:3.7.3

ARG http_proxy=http://10.15.1.10:8080
ARG https_proxy=http://10.15.1.10:8080

WORKDIR /app

ADD requirements.txt /app
RUN pip install --proxy 10.15.1.10:8080 --no-cache-dir -r requirements.txt

COPY main.py /app

EXPOSE 8080
