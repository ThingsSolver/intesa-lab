FROM python:3.7.3

WORKDIR /app

ADD requirements.txt /app
RUN pip install --no-cache-dir -r requirements.txt

COPY main.py /app

EXPOSE 8080
