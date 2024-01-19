DO NOT USE THIS! I'M NOT VERY CONFIDENT ABOUT THE SAFETY OF THIS

Внимание! Я особо не буду поддерживать этот код, а также возможно этот не соблюдает законы о хранение данных некоторых страз, над этим думайте сами

Например тут сломанная база данных которая не хранит много где IP (нормальную можно взять в ветке old), а также сервер вроде не хранит удалённын уровни

# 1.5 GDPS
Basically a Geometry Dash Server Emulator but for 1.5

Required version of PHP: 5.4+ (tested up to 7.3.11 by Cvolton)

### Feel like I've seen this before
This used to be a fork of Flux3on's 1.6 GDPS, but I guess the original repository got deleted, so this is the main now.

### Really Basic Setup
1) Upload the files on a webserver
2) Import database.sql into a MySQL/MariaDB database
3) Edit the links in config/connection.php
4) Edit the links in libgame.so for armeabi, armeabi-v7, and x86

### Credits
Using this for XOR encryption - https://github.com/sathoro/php-xor-cipher - (incl/lib/XORCipher.php)

Using this for cloud save encryption - https://github.com/defuse/php-encryption - (incl/lib/defuse-crypto.phar)

Most of the stuff in generateHash.php has been figured out by pavlukivan and Italian APK Downloader, so credits to them

Cvolton for making this server software in the first place, epic stuff dude - https://github.com/Cvolton/GMDprivateServer (GNU General Public License v3.0) 

Top Week ingame made possible by Absolute
