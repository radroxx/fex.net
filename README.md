# fex.net cli

## !!!ATTENTION!!!
Fex.com ввел скрытую каптчу на login и, к сожалению, обходить каптчи не входит в функционал данного проекта. Остается вариант работать с анонимными папками, но без привлекательного тарифа загружать файлы на fex нет не какого смысла. Проще воспользоваться любым другим облачным хранилищем с помощью https://rclone.org/. Что-либо делать считаю не целесообразным до момента пока fex.net не сделает хотя бы возможность работать через api key.

## Что это такое ?
Это консольная утилита для работы с fex.net.
## Как с ней работать ?
### Linux
```
$ apt-get install busybox curl
$ sudo curl -L -o /bin/fex https://raw.githubusercontent.com/radroxx/fex.net/master/fex
$ sudo chmod +x /bin/fex
```
busybox не обязателен.
### Android (Termux)
```
$ pkg install busybox curl
$ curl -L -o fex https://raw.githubusercontent.com/radroxx/fex.net/master/fex
$ chmod +x fex
```
busybox не обязателен.
### Windows
Скачать:
* [Busybox-win] <https://frippery.org/busybox/>
* [CURL-win] <https://curl.haxx.se/windows/>
```
$ export BUSYBOX=C:/Busybox.exe
$ export CURL=C:/curl.exe
```
### Mac OS
Должно работать и так.
