FROM golang:1.22-alpine 

WORKDIR /app

COPY . .

RUN go build -o main .

#RUN apt update && apt install -y curl

CMD ["./main"]
