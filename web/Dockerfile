FROM nginx:latest

WORKDIR /etc/nginx

COPY nginx.conf .

COPY dist/. /var/www/ledger-admin/

EXPOSE 8001

EXPOSE 3001

