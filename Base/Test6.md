# Тест 6

1. Какое программное обеспечение нужно для установки приложений в графическом окружении
```sh
# Dnf Dragora (РЕД ОС 7.3)
# Yum Extender (РЕД ОС 7.2)
```
2. Репозиторий это
```sh
Хранилище пакетов, принадлежащих одному дистрибутиву
```
3. Каждый пакет RPM имеет название, которое состоит из нескольких частей: Например: `mplayer-1.2.1-4.el7.x86_64.rpm`
```sh
# название программы
# версия программы
# номер релиза
# архитектура, под которую собран пакет
```
4. Основные операции RPM:
```sh
# Установка пакета: rpm ‑i  <файл пакета>
# Обновление пакета: rpm ‑U  <файл пакета>
# Удаление пакета: rpm ‑e  <пакет>
# Получение информации о пакете: rpm ‑q <пакет>
# Проверка пакета: rpm ‑V  <пакет>
```
5. Файл RPM — это ...
```sh
# архив содержащий не только программу, но и служебные файлы, необходимые для правильной установки программы
```
6. Напишите команду проверки установленного пакета nano с помощью программы `rpm`
```sh
rpm -V nano
```
7. Файлы настроек репозитория хранятся в папке ...
```sh
/etc/yum.repos.d/
```
8. Напишите команду (`dnf` или `yum`) установки приложения `mplayer`. Команду написать без сокращений.
```sh
yum install mplayer
```
9. Напишите команду (`dnf` или `yum`) удаления приложения `mplayer`. Команду написать без сокращений.
```sh
yum remove mplayer
```
10. Команда поиска установленного пакета `VLC`
```sh
rpm -qa | grep vlc
dnf list installed VLC
```
