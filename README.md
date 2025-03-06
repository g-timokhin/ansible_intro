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

**8**

Успешно запущен playbook на окружении prod.yml
Пароль был запрошен

![image](https://github.com/user-attachments/assets/c1b24ac5-1a4e-425c-9ad3-e45ef0be42e8)

![image](https://github.com/user-attachments/assets/5b8fc465-c62d-43f5-a967-ce69de2d928d)


**9**

Список плагинов для подключения

![image](https://github.com/user-attachments/assets/dac5545d-c862-4934-bde5-3fc6b2e81b92)

**10**

Добавлена новая группа хостов

![image](https://github.com/user-attachments/assets/f06b4ec2-a9f4-4043-a440-9e8640b21a4a)

**11**

Успешно запущен playbook

![image](https://github.com/user-attachments/assets/223d5fcc-78ed-40ec-8469-d22494744a23)

![image](https://github.com/user-attachments/assets/e69caf9f-0335-4274-b840-965ed382d339)

![image](https://github.com/user-attachments/assets/7cedca8e-cfba-494c-9a83-3e7d4278cd52)


























































