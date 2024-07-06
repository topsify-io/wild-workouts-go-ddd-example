FROM golang:1.23rc1

ARG SERVICE

RUN mkdir /internal
COPY . /internal
WORKDIR /internal/$SERVICE
RUN go build -o /app .

CMD ["/app"]
