## Telegram CrypT0R bot to crypt your files remotely (made with python 3.8) | Created by F4RB3R
![Made with Python](https://img.shields.io/badge/Made%20with-Python-3572A5.svg)

```
pip install -r requirements.txt

OR

pip install pyTelegramBotAPI
pip install cryptography
pip install pycryptodome or if you use Windows pip install pycryptodomex
```

## Bot Commands:

```
------------------------------
<Welcome to Help>
------------------------------
Bot Commands:
[01] Start
[ /] /start
[02] Help.
[ /] /help
[03] Encrypting one file.
[ /] /encryptone - encrypt only one file
[03] Encrypting all data.
[ /] /encryptall - encripts all files in directory
[04] Shutdown PC.
[ /] /shutdown
[05] Restart PC.
[ /] /restart
------------------------------
<Created by F4RB3R>
------------------------------
'''

## How to use?
```
First of all you need to run GenerateKey.py to generate key.key
Put key.key and private.pem to usb drive, this is necessary so that in the future you can decrypt the files
In the TeleCrypT0R.py file, insert name of file that be encrypted, bot token and your ID(@userinfobot)
In function walk insert your directory, remember, all files there will be encrypted
```
## Как использовать?
```
Для начала вам нужно запустить GenerateKey.py чтобы сгенерировать файл key.key
Скопируйте файл key.key на флешку, это нужно для того, чтобы в дальнейшем вы могли расшифровать файл
В файле TeleCrypT0R.py вставьте имя файла для зашифровования, токен бота и ваш айди(@userinfobot)
В функцию walk вставьте свой каталог, запомните, все файлы там будут зашифрованы
```
