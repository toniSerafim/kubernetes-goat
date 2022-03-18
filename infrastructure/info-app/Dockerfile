FROM python:3.10-alpine
LABEL MAINTAINER="Madhu Akula" INFO="Kubernetes Goat"

COPY app.py /app.py

RUN pip install flask

EXPOSE 5000

CMD [ "python", "/app.py" ]
