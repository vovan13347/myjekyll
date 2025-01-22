# myjekyll

# Создание сертификата
    openssl req -newkey rsa:2048 -nodes -keyout localhost.key -x509 -days 365 -out localhost.crt

# Запуск с сертификатом
    bundle exec jekyll serve --ssl-key localhost.key --ssl-cert localhost.crt

### Как запустить
_Версия ruby - ruby 3.0.2p107_
____

1. создать проект: `jekyll new nameproject`

2. установить bundle: `bundle install`

3. запустить: `bundle exec jekyll serve`