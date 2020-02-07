FROM golang:1.13.7

WORKDIR /go/src/ledger-api

COPY . .

EXPOSE 8080

CMD ["/bin/bash", "/go/src/ledger-api/script/build.sh"]