FROM alpine:3.5
RUN apk add --no-cache chicken python3
RUN mkdir -p /app
ADD occult_server.tar.bz2 /app
ADD runner.py /app/runner.py
WORKDIR /app

CMD /app/runner.py
