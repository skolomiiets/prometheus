FROM python:3.7
LABEL maintainer="serg.kolomiiets@gmail.com"
LABEL labs="prometheus"
ENV PYTHONUNBUFFERED 1
COPY app-entrypoint.sh /
COPY requirements.txt /
RUN pip install --no-cache-dir -r /requirements.txt
