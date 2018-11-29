# fex.net cli
## Что это такое ?
Это консольная утилита для работы с fex.net.
## Как с ней работать ?
### Linux
'''sh
$ apt-get install busybox curl
$ sudo curl -L -o /bin/fex https://raw.githubusercontent.com/radroxx/fex.net/master/fex
$ sudo chmod +x /bin/fex
$ TOKEN='fex create'
$ fex file ${TOKEN} add /etc/hostname
$ fex file ${TOKEN} list
$ fex url ${TOKEN}
'''
### Android (Termux)
'''sh
$ pkgs install busybox curl
$ curl -L -o fex https://raw.githubusercontent.com/radroxx/fex.net/master/fex
$ sudo chmod +x fex
$ TOKEN='./fex create'
$ ./fex file ${TOKEN} add /etc/hostname
$ ./fex file ${TOKEN} list
$ ./fex url ${TOKEN}
'''
### Windows
Скачать:
* [Busybox-win] <https://frippery.org/busybox/>
* [CURL-win] <https://curl.haxx.se/windows/>
'''sh
$ export BUSYBOX=C:/Busybox.exe
$ export CURL=C:/curl.exe
$ TOKEN='./fex create'
$ ./fex file ${TOKEN} add /etc/hostname
$ ./fex file ${TOKEN} list
$ ./fex url ${TOKEN}
'''
### Mac OS
Где взять Busybox для Mac OS ?