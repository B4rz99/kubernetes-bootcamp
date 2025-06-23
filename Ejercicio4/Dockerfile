FROM ubuntu

RUN apt update && apt install -y curl

COPY script.sh /scripts/

RUN chmod 744 /scripts/script.sh

CMD ["/scripts/script.sh"]
