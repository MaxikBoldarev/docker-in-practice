# docker-in-practice

## Задача 1
_______________________
Ссылка на форк https://github.com/MaxikBoldarev/shvirtd-example-python
<img width="1604" height="38" alt="image" src="https://github.com/user-attachments/assets/0fcd09d9-103c-45ac-93ed-458cfe867531" />
<img width="1836" height="665" alt="image" src="https://github.com/user-attachments/assets/aa757d1f-39f2-431e-a941-a98b5ccf7933" />
_______________________
## Задача 3
_______________________
<img width="1550" height="645" alt="image" src="https://github.com/user-attachments/assets/f83daf3a-c281-498c-b8ff-0de4d22f530d" />
<img width="974" height="58" alt="image" src="https://github.com/user-attachments/assets/03638c07-1edb-47c3-ad55-306d2b59939d" />
<img width="1126" height="625" alt="image" src="https://github.com/user-attachments/assets/2a59dce9-8f62-4064-b5ba-50ff57bf5c8f" />
_______________________

## Задача 4
_______________________
<img width="1041" height="299" alt="image" src="https://github.com/user-attachments/assets/2da44238-b49a-48e8-a95f-a0ed1c4e1952" />  

Задача 4
Запустите в Yandex Cloud ВМ (вам хватит 2 Гб Ram).
Подключитесь к Вм по ssh и установите docker.
Напишите bash-скрипт, который скачает ваш fork-репозиторий в каталог /opt и запустит проект целиком.
Зайдите на сайт проверки http подключений, например(или аналогичный): https://check-host.net/check-http и запустите проверку вашего сервиса http://<внешний_IP-адрес_вашей_ВМ>:8090. Таким образом трафик будет направлен в ingress-proxy. Трафик должен пройти через цепочки: Пользователь → Internet → Nginx → HAProxy → FastAPI(запись в БД) → HAProxy → Nginx → Internet → Пользователь
(Необязательная часть) Дополнительно настройте remote ssh context к вашему серверу. Отобразите список контекстов и результат удаленного выполнения docker ps -a
Повторите SQL-запрос на сервере и приложите скриншот и ссылку на fork.


Задача 6
Скачайте docker образ hashicorp/terraform:latest и скопируйте бинарный файл /bin/terraform на свою локальную машину, используя dive и docker save. Предоставьте скриншоты действий .

Задача 6.1
Добейтесь аналогичного результата, используя docker cp.
Предоставьте скриншоты действий .
