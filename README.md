## Подготовка к выполнению ##

**1.** Ansible версии 2.18.1 установлен

![image](https://github.com/user-attachments/assets/2029ea7a-8520-4935-a3af-b4b262b8ca19)

**2.** Создан [репозиторий](https://github.com/user-attachments/assets/4287724f-3599-46c6-9b2b-329b6543e6cf)

**3.** В репозиторий [перенесена](https://github.com/g-timokhin/ansible_intro/tree/master/playbook) директория playbook

## Основная часть ##

**1.** Playbook на окружении test.yml успешно запущен

![image](https://github.com/user-attachments/assets/9ad8c6cd-bbd4-493e-87d2-1fbda934184d)

![image](https://github.com/user-attachments/assets/b7b51ada-28d1-438b-8071-80a8840d7ba3)

факт some_fact имеет значение 12

**2.**

![image](https://github.com/user-attachments/assets/088dff61-048d-480a-99b6-d1c28090895c)

**3** 

Создано окружение: запущено два докер-контейнера -- centos7 и ubuntu --  в каждый установлен интерпретатор python
Соответственно отредактирован файл prod.yml
(Для контейнера centos7 выбран образ almalinux, т.к centos7 не поддерживается в достаточной мере -- интерпретатор python нормально в него не устанавливается)

![image](https://github.com/user-attachments/assets/4e4e127c-c3b1-4399-bca7-2f7355790037)

![image](https://github.com/user-attachments/assets/39b20504-fb27-4352-b094-7b4af917ccea)

**4**

Успешно проведен запуск playbook на окружении prod.yml

![image](https://github.com/user-attachments/assets/b23eb63a-29b6-441e-b356-4ed6a05e7027)

![image](https://github.com/user-attachments/assets/e0b527e8-cb8d-49f7-abf2-638d5d6c25ac)

Для хоста ubuntu факт somefact имеет значение deb

Для хоста centos7 факт somefact имеет значение el

**5, 6**

![image](https://github.com/user-attachments/assets/2d9f019c-b1bc-4db3-9deb-14dad771639e)

**7**

Зашифровка прошла успешно

![image](https://github.com/user-attachments/assets/9d2b53f6-071c-4257-8f40-8d2c22c8beb2)

![image](https://github.com/user-attachments/assets/f9c4403a-a813-465a-8cb4-f04e9d46df3e)











































