FROM golang:1.19
WORKDIR /app
COPY go.* ./
COPY *.go ./
RUN go build -o main .
EXPOSE 8080
CMD ["./main"]