# Итоговый тест

1. Распределите, какое графическое окружение рабочего стола в каких системах устанавливается с установочного образа.
```sh
# GNOME - не используется в РЕДОС
# KDE - не используется в РЕДОС
# MATE - РЕДОС 7.2 и РЕДОС 7.3
# Cinnamon - РЕДОС 7.2
# Xfce - не используется в РЕДОС
# Unity - не используется в РЕДОС
# LXDE - не используется в РЕДОC
```
2. Какой офисный пакет входит в состав РЕД ОС?
```sh
# libreoffice
```
3. С помощью какой команды можно выполнить какую-либо программу от имени любого другого пользователя?
```sh
su <имя пользователя> -с <имя команды>
```
4. С помощью какой консольной утилиты пользователь может сменить свой пароль в системе?
```sh
passwd
```
5. Обладая «обычными» правами, пользователь может включать себя в другие группы пользователей.
```sh
# Неверно
```
6. О том, что файл можно выполнить, система узнает
```sh
# только по его атрибутам
```
7. Пользователь `ivanov` является членом только одной группы — `ivanov`. Он запустил на выполнение файл `test.sh`, имеющий следующие атрибуты: `-rwxrw-rw- 1 petrov ivanov 120 янв 1 00:01 test.sh`
```sh
# Неверно
```
8. Какое из определений «жёсткой» ссылки верно?
```sh
# представляет собой другое имя файла
```
9. Какой пакет отвечает в РЕД ОС за поддержку системы печати?
```sh
cups
```
10. Какая команда в РЕД ОС используется для получения справки по команде `ls`?
```sh
ls --help
man ls
info ls
```
11. Что из перечисленного является файловыми системами, поддерживаемыми в РЕД ОС.
```sh
xfs
ext4
ext2
```
12. Каков будет результат выполнения команды `ln -s source.txt soft.link`
```sh
# создает символическую ссылку на source.txt
```
13. Какой командой в РЕД ОС можно увидеть свободное место на дисках?
```sh
df
```
14. Какое сочетания клавиш скрывает панели в `midnight commander`?
```sh
# ctrl+O
```
15. Как добавить пользователя `testuser` в группу `testgroup`
```sh
gpasswd -a testuser testgroup
usermod -a -G testgroup testuser
```
16. Как сделать владельцем файла `tfile` пользователя `tuser` и группу `tgroup`
```sh
# hown tuser:tgroup tfile
# chown tuser.tgroup tfile
```
17. Какой командой запустить службу `cups`?
```sh
systemctl start cups
```
18. Какой загрузчик ядра используется в РЕД ОС по умолчанию?
```sh
# grub2
```
19. С целью запуска процесса в фоне, необходимо в конце командной строки поставить символ
```sh
&
```
20. Посмотреть права доступа на файл `/bin/passwd`
```sh
ls -l /bin/passwd
```
