FROM python:3.14.0b3-alpine3.21

WORKDIR /app

COPY . .

RUN pip install flask

#RUN apt update && apt install -y curl

CMD ["python", "app.py"]
