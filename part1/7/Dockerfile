FROM ubuntu:16.04

WORKDIR /curler
COPY . .
RUN chmod +x ./curler.sh

RUN apt-get update && apt-get install -y curl wget

CMD ["./curler.sh"]
