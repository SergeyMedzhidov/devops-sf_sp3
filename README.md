# devops-sf_sp3
- Деплой мониторинга на сервер srv:
```diff
$ git clone https://github.com/devops-sf_sp3.git
$ cd devops-sf_sp3 
```
- Изменить ip адрес (ip-server) и порт таргет сервера для запросов(prometheus/prometheus.yml, alert.rules)
````
$ docker-compose up -d
````
