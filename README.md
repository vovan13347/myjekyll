# myjekyll

# Создание сертификата
    openssl req -newkey rsa:2048 -nodes -keyout localhost.key -x509 -days 365 -out localhost.crt

# Запуск с сертификатом
    bundle exec jekyll serve --ssl-key localhost.key --ssl-cert localhost.crt