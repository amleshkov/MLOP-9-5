# Домашняя работа к занятию “Мониторинг”

### Алерты в Prometheus:
- `jenkins_down` - состояние контейнера с Jenkins
- `jenkins_high_cpu` - нагрузка по CPU для контейнера с Jenkins
- `jenkins_high_memory` - потребление памяти контейнером с jenkins
- `high_cpu_load` - нагрузка по CPU на хосте с Docker
- `high_memory_load` - потребление памяти на хосте с Docker
- `high_storage_load` - потребление дискового пространства на хосте с Docker
- `monitor_service_down` - состояние службы мониторинга

### Дашборды в графана
- Docker containers - статистика по запущенным контейнерам
- Docker Host - статистика хоста с Docker
- Monitor Services - статистика служб мониторинга (Prometheus, Alertmanager etc.)
- Nginx - статистика сервиса Nginx

### Описание дашборда Docker Containers

IMAGE
- CPU Load - нагрузка на CPU
- CPU Cores - количество ядер
- Memory Load - объем занятой RAM %
- Used Memory - объем занятой RAM MiB
- Storage load - занятый объем хранилища aufs %
- Used Storage - занятый объем хранилища GiB
- Running Containers - количество запущенных контейнеров
- System Load - Load Average для хоста с Docker
- I/O Usage - нагрузка на дисковую подсистему
- Container CPU Usage - график потребления CPU для контейнеров
- Container Memory Usage - график потребления памяти для контейнеров
- Container Cached Memory Usage - график объема кеша для контейнеров
- Container Network Input - график нагрузки на сеть для контейнеров Input
- Container Network Output - график нагрузки на сеть для контейнеров Otput
