# restart_containers

У файлі оголошуються 2 змінні:
1. containers - перелік контейнерів, що будуть перезавантажені
2. timeout - блокування перезавантаження, якщо після попереднього не пройшло timeout секунд 

Приклад файла restart_containers_var.yml 
timeout: 3600
containers:
  - scg_crewisor_ui
  - scg_crewisor_nginx

