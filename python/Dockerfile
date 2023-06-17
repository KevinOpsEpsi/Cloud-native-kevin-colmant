FROM python:3.8.17-slim-bullseye

COPY Blur-Detection-Web-App /opt/app

COPY . /opt/app
WORKDIR /opt/app
RUN pip install -r requirements.txt

LABEL maintainer="Jean-Baptiste D"
LABEL version="1.0"

EXPOSE 5000

ENTRYPOINT ["python", "main.py"]