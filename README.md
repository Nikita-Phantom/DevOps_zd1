# DevOps_zd1


### 2 и 3. Создание ВМ.


Скачал ubuntu 26.04.

Успешно установили вмку.

<img width="575" height="590" alt="image" src="https://github.com/user-attachments/assets/6ba4b3a0-b7b8-494f-b568-a79bd969c0a5" />

Проверка связи с внешним миром.

<img width="751" height="414" alt="image" src="https://github.com/user-attachments/assets/2ee610e3-ab6f-4c92-b581-31e627c686c6" />

Пробрасываем порт.

<img width="1117" height="400" alt="image" src="https://github.com/user-attachments/assets/c1e83e2b-b9e0-4c21-85c6-ffd4afa78f55" />


### 4. SSH


Устанавливаем ssh сервер на вмку.

<img width="684" height="136" alt="image" src="https://github.com/user-attachments/assets/0487712b-09d3-48f2-952f-88780a153ec3" />

Входим по паролю

<img width="740" height="829" alt="image" src="https://github.com/user-attachments/assets/9ec144e6-8874-4413-8687-73c74d57b659" />


### 5. Диагностирование системы.

uname

<img width="914" height="40" alt="image" src="https://github.com/user-attachments/assets/66428087-d75f-4788-9105-0570bfcff61b" />


lsb_release

<img width="381" height="105" alt="image" src="https://github.com/user-attachments/assets/88bd7268-c5dd-43c4-abf8-e647e2f06e98" />


top

<img width="883" height="900" alt="image" src="https://github.com/user-attachments/assets/e4238afb-4feb-4d9a-8213-d826998a0e7d" />


ls 

<img width="482" height="179" alt="image" src="https://github.com/user-attachments/assets/3b405037-fa6b-4df1-a89f-db784dd58879" />


lsblk

<img width="410" height="165" alt="image" src="https://github.com/user-attachments/assets/d885da63-2603-4a47-872d-6772d1f8fbac" />


fdisk

<img width="577" height="545" alt="image" src="https://github.com/user-attachments/assets/50ab285c-6d92-4a85-b12a-2fa6a077cc2c" />

mount - команда для монтирования

shown - команда для изменения владельца

shmod - команда для изменения прав доступа


### 6. Диагностирование сети

ip a

<img width="840" height="277" alt="image" src="https://github.com/user-attachments/assets/467cfdda-ec99-416e-b973-cd27dd34b7ab" />

traceroute

<img width="617" height="72" alt="image" src="https://github.com/user-attachments/assets/031c196d-cc90-4233-baff-53536db46bbf" />

### 7. Установка пакетов Python и Git

<img width="910" height="711" alt="image" src="https://github.com/user-attachments/assets/16ac2a57-19f4-4266-b056-d1715def2ce2" />


### 8, 9 и 10. Создание нового пользователя и SSH по ключу.


Создал нового пользователя tester

<img width="347" height="40" alt="image" src="https://github.com/user-attachments/assets/d752d172-fe00-414b-a219-c07abaafb082" />


Сгенерировал SSH ключ и положил .pub в /.ssh/authorized_keys и назначил для tester все права на папки.

<img width="699" height="117" alt="image" src="https://github.com/user-attachments/assets/b1d4cc85-3761-40f8-95d0-bad1a97c12e5" />


Теперь вход происходит по ключу

<img width="639" height="637" alt="image" src="https://github.com/user-attachments/assets/2d7fac08-afa5-4547-9be4-13442640bcf6" />


Через visudo задал для tester использование sudo без пароля

<img width="519" height="174" alt="image" src="https://github.com/user-attachments/assets/2ac2b9b8-4df6-42ae-816f-228f9590a2f1" />

<img width="484" height="90" alt="image" src="https://github.com/user-attachments/assets/c74f2d55-3993-47fc-82ea-4d8a9d075f12" />


### 11. VS Code и подключение к вм по ssh


Установил плагин Remote - SSH и настроил конфиг для подключения. Успешно подключились по SSH к ВМ через VS Code

<img width="1920" height="949" alt="image" src="https://github.com/user-attachments/assets/c15a408f-1d04-41f7-ab04-ebe37d4be1bf" />


