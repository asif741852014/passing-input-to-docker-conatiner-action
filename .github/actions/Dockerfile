FROM alpine:3.10
WORKDIR /var/lib
COPY . .
RUN chmod +x ./entrypoint.sh
ENTRYPOINT ["sh","-c","/var/lib/entrypoint.sh"]