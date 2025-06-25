#FROM python:3.14.0b3-alpine3.21

#WORKDIR /app

#COPY . .

#RUN pip install flask

#RUN apt update && apt install -y curl

#CMD ["python", "app.py"]

#FROM python:3.11
#WORKDIR /app
#COPY . .
#RUN pip install flask uvicorn
#CMD ["uvicorn", "app:app", "--host", "0.0.0.0", "--port", "8002"]

FROM python:3.11

WORKDIR /app
COPY . .

RUN apt update &&  apt install -y curl
RUN pip install flask

EXPOSE 8002
CMD ["python", "app.py"]

