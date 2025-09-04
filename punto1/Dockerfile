FROM alpine:3.20

WORKDIR /app

RUN apk add curl

COPY mensaje.txt .

EXPOSE 2500

CMD ["cat", "mensaje.txt"]
