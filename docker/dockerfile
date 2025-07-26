FROM docker:24.0.6-cli

WORKDIR /app

COPY . .

RUN apk add --no-cache docker-compose bash

CMD ["sh", "-c", "docker-compose up"]
