# Покупка аккаунтов
Сайты:
https://accsmarket.com/ru/catalog/drugie-akkaunty/telegram

Вам выдадут ссылки, где скачать папку с аккаунтом телеграмма, скачивайте и запускайте.

## Получения сессий для telethon и pyrogram
### Получения api_id и api_hash рассказано на сайте
https://tlgrm.ru/docs/api/obtaining_api_id

Первое, что нужно настроить, так добавить сами аккаунты в файл api_users.txt в папке проекта session/api_users.
```
\\Формат добавление
номер_телефона;api_id;api_hash
```
### Важно!
#### Обязательно добавляйте разделитель ";"
Пример:

![image](https://user-images.githubusercontent.com/63918733/133865943-5ed09383-3c55-4852-9060-d86620d9c145.png)

##### Запускаем скрипт invite_chat.py
```python
# Версия Python 3.9
# Запуск скрипта Windows

py invite_chat.py
```

После нужно пройти авторизацию, 1 написан номер, его и вводим в поле "Enter phone number or bot token"

![image](https://user-images.githubusercontent.com/63918733/133865627-045a7ac8-83f2-4510-adb9-98ccae1fd0b4.png)

### Все сессии хранятся в папке session проекта, её нужно проходить всего один раз для каждого нового акка.
# Получение юзеров из чата
##### Запускаем скрипт invite_chat.py
```python
# Версия Python 3.9
# Запуск скрипта Windows

py pars_user.py название чата
```
После как он спарсит участников, они появятся в файле data/group_list.text
