# FROM alpine:3.14
# FROM nginx
FROM python:3

WORKDIR /usr/src/app/

# COPY html /usr/share/nginx/html
COPY python/demo.py $WORKDIR

# CMD ["echo", "Hello World"]

CMD ["python", "./demo.py"]















# syntax=docker/dockerfile:1
# FROM python:3.7-alpine
# WORKDIR /code
# ENV FLASK_APP=app.py
# ENV FLASK_RUN_HOST=0.0.0.0
# RUN apk add --no-cache gcc musl-dev linux-headers
# COPY python/requirements.txt requirements.txt
# RUN pip install -r requirements.txt
# EXPOSE 5000
# COPY python/app.py .
# CMD ["flask", "run"]