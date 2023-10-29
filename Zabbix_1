# Домашнее задание к занятию «Система мониторинга Zabbix»

<details>

В практике есть 2 основных и 1 дополнительное (со звездочкой) задания. Первые два нужно выполнять обязательно, третье - по желанию и его решение никак не повлияет на получение вами зачета по этому домашнему заданию, при этом вы сможете глубже и/или шире разобраться в материале. 

Пожалуйста, присылайте на проверку всю задачу сразу. Любые вопросы по решению задач задавайте в чате учебной группы.

### Цели задания
1. Научиться устанавливать Zabbix Server c веб-интерфейсом
2. Научиться устанавливать Zabbix Agent на хосты
3. Научиться устанавливать Zabbix Agent на компьютер и подключать его к серверу Zabbix 

### Чеклист готовности к домашнему заданию
- [ ] Просмотрите в личном кабинете занятие "Система мониторинга Zabbix" 

### Инструкция по выполнению домашнего задания

1. Сделайте fork [репозитория c шаблоном решения](https://github.com/netology-code/sys-pattern-homework) к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw).
2. Выполните клонирование этого репозитория к себе на ПК с помощью команды `git clone`.
3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
   - впишите вверху название занятия и ваши фамилию и имя;
   - в каждом задании добавьте решение в требуемом виде: текст/код/скриншоты/ссылка;
   - для корректного добавления скриншотов воспользуйтесь инструкцией [«Как вставить скриншот в шаблон с решением»](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md);
   - при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в [инструкции по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md).
4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`).
5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
6. Любые вопросы задавайте в чате учебной группы и/или в разделе «Вопросы по заданию» в личном кабинете.

</details>

---

### Задание 1 

Установите Zabbix Server с веб-интерфейсом.

#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Установите PostgreSQL. Для установки достаточна та версия что есть в системном репозитороии Debian 11
3. Пользуясь конфигуратором комманд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache
4. Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server

#### Требования к результаты 
1. Прикрепите в файл README.md скриншот авторизации в админке
2. Приложите в файл README.md текст использованных команд в GitHub

### Ответ

- Установка PostgreSQL.

<details>

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/1a478d9c-b9c8-4ffa-b177-61f61cf1ded9)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/c36efb22-2c41-41c1-b92f-fe3d8b3425c5)

</details>

- Установка Zabbix-server.

<details>

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/ca6c26df-3645-43e8-b56b-1c343111c10f)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/d0161ebc-d91f-4c13-a7d2-51ae00b79aa7)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/c02ef913-3a93-4012-8c15-44825c8cb030)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/2976bb98-ee94-49ec-b28b-e9685f39bf6c)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/a024b1c2-bfd0-49c8-9491-cbee32874768)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/430e49ef-7df5-415e-a337-fe47cf296f8a)

</details>

- Запуск Zabbix-server.

<details>

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/8020e570-f1e8-465b-b6de-b55c0bac122b)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/610f2f23-cf96-400e-9e48-b6c3677e93e4)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/727e95ec-6038-4bb1-b85e-9ef7c17a9284)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/03a7fd54-2fa9-4643-9332-96eaa37e2cef)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/d76cd037-cfa9-4979-935e-4b025baa28bb)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/ffb628db-f26e-4ca0-a092-0a5e7ad9c160)
  
</details>

---

### Задание 2 

Установите Zabbix Agent на два хоста.

#### Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
5. Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов

#### Требования к результаты 
1. Приложите в файл README.md скриншот раздела Configuration > Hosts, где видно, что агенты подключены к серверу
2. Приложите в файл README.md скриншот лога zabbix agent, где видно, что он работает с сервером
3. Приложите в файл README.md скриншот раздела Monitoring > Latest data для обоих хостов, где видны поступающие от агентов данные.
4. Приложите в файл README.md текст использованных команд в GitHub

### Ответ

- Установка Zabbix-агентов на две машины.

<details>

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/cb0a9422-afbf-4b86-8608-e6eaec05c3d6)

</details>



- Подключение агентов к Zabbix-серверу.

<details>

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/266b0047-a5c5-4bad-9d3f-43bfebcf5e59)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/c592488f-5f3a-45c8-a023-7f14b17241fa)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/79bec362-b284-4485-aa9b-c59331766820)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/78a2e77f-5fb5-4a8e-8795-9e96b0954d69)

![image](https://github.com/Ivashka80/Zabbix_p1/assets/121082757/c9052900-375d-4acf-acbe-934da4287168)

</details>






---
## Задание 3 со звёздочкой*

<details>

Установите Zabbix Agent на Windows (компьютер) и подключите его к серверу Zabbix.

#### Требования к результаты 
1. Приложите в файл README.md скриншот раздела Latest Data, где видно свободное место на диске C:
--- 

## Критерии оценки

1. Выполнено минимум 2 обязательных задания
2. Прикреплены требуемые скриншоты и тексты 
3. Задание оформлено в шаблоне с решением и опубликовано на GitHub

</details>


