# Конфигурация logstash в docker-контейнере для реиндекса индексов nginx в elastic

## Запуск
- Задать параметры в файле [config/logstash.conf](config/logstash.conf), в input -> hosts, user, password, index, в output -> hosts, user, password, index;
- Задать количество потоков в файле [config/logstash.yml](config/logstash.yml);
- Запустить logstash, выполнив команду `docker-compose up -d`


