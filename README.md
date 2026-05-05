# Отчет по лабораторной работе 00

## Цель 

Разобраться с базовыми настройками линукса, создать персональный токен и 
скинуть его в соответтствующий файля, проверить на наличие библиотек и
скачать нужное

###Ход работы

### Привязка заполнение гугл формы и гитхаба 

Результат:логин qNetayS

### Проверка наличия нужных библиотек
```
$ cmake --version
$ curl --version
$ git --version
$ g++ --version
$ hub --version
$ make --version
$ subl --version
$ tree --version
$ wget --version
$ openssl --version
```
Результат: все кроме curl не найдено

###Скачивание нужных файлов
для этого я использовал команду 

```shell 
$ sudo apt install -y buils-essential cmake surl git wget tree openssl
$ sudo snap install hub --classic
```
проверка:
```shell
$ g++ --version && make -- version &&cmake --version && gh -- version
```

Результат:
```shell
Cmake suite maintained and supported by Kitware
git version 2.39.2
g++(Debian 12.2.0-14) 12.2.0
Copyright (c) 2022 Free Software Foundation, Inc.
GNU Make 4.3
Built for x86_64-pc-linux-gnu
tree v2.1.1 (c) 1996-2022 by Steve Baker,et,al.
OpenSSL 3.0.11 19 Sep 2023 
```

### Создание персонализированного токена и введение его в файл
Переходим на сайт hhtps://github.com/settings/tokens/new
Создаем токет(qNetaySToken)
создаем в директории Timp файл gist_token.txt куда скидываем ключ токена

