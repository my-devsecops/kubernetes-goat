FROM python:alpine
LABEL MAINTAINER="Ayman Mahmoud" INFO="Kubernetes Goat"

COPY app.py /app.py

RUN pip install flask

EXPOSE 5000

CMD [ "python", "/app.py" ]
