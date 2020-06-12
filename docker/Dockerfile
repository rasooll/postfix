FROM alpine:latest
RUN apk add postfix cyrus-sasl cyrus-sasl-plain cyrus-sasl-login
EXPOSE 25
COPY main.cf /etc/postfix/main.cf
CMD ["postfix", "start-fg"]
