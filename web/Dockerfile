FROM nginx:1.17

WORKDIR /etc/nginx

COPY nginx.conf .

COPY dist/. /var/www/ledger-admin/

EXPOSE 8001

