```
pi@chris-pi:~ $ pip3 -V
pip 18.1 from /usr/lib/python3/dist-packages/pip (python 3.7)
pi@chris-pi:~ $ pip3 list
Package             Version
------------------- -----------
asn1crypto          0.24.0
astral              2.2
astroid             2.1.0
asttokens           1.1.13
automationhat       0.2.0
bandcamp-downloader 0.0.12
beautifulsoup4      4.7.1
blinker             1.4
blinkt              0.1.2
buttonshim          0.0.2
Cap1xxx             0.1.3
certifi             2018.8.24
chardet             3.0.4
Click               7.0
colorama            0.3.7
colorzero           1.1
cookies             2.2.1
cryptography        2.6.1
cupshelpers         1.0
demjson3            3.0.5
docopt              0.6.2
docutils            0.14
drumhat             0.1.0
entrypoints         0.3
envirophat          1.0.0
ExplorerHAT         0.4.2
Flask               1.0.2
fourletterphat      0.1.0
geographiclib       1.52
geopy               2.2.0
gpiozero            1.5.1
html5lib            1.0.1
idna                2.6
isort               4.3.4
itsdangerous        0.24
jdcal               1.4.1
jedi                0.13.2
Jinja2              2.10
keyring             17.1.1
keyrings.alt        3.1.1
lazy-object-proxy   1.3.1
logilab-common      1.4.2
lxml                4.3.2
MarkupSafe          1.1.0
mccabe              0.6.1
microdotphat        0.2.1
mock                4.0.3
mote                0.0.4
motephat            0.0.3
mutagen             1.45.1
mypy                0.670
mypy-extensions     0.4.1
numpy               1.16.2
oauthlib            2.1.0
olefile             0.46
pantilthat          0.0.7
parso               0.3.1
pexpect             4.6.0
pgzero              1.2
phatbeat            0.1.1
pianohat            0.1.0
picamera            1.13
piglow              1.2.5
pigpio              1.78
Pillow              5.4.1
pip                 18.1
psutil              5.5.1
pycairo             1.16.2
pycrypto            2.6.1
pycups              1.9.73
pygame              1.9.4.post1
Pygments            2.3.1
PyGObject           3.30.4
pyinotify           0.9.6
PyJWT               1.7.0
pylint              2.2.2
pyOpenSSL           19.0.0
pyserial            3.4
pysmbc              1.0.15.6
python-apt          1.8.4.3
pytz                2021.3
pyxdg               0.25
rainbowhat          0.1.0
reportlab           3.5.13
requests            2.21.0
requests-oauthlib   1.0.0
responses           0.9.0
roman               2.0.0
RPi.GPIO            0.7.0
RTIMULib            7.2.1
scrollphat          0.0.7
scrollphathd        1.2.1
SecretStorage       2.3.1
Send2Trash          1.5.0
sense-hat           2.2.0
setuptools          40.8.0
simplejson          3.16.0
six                 1.12.0
skywriter           0.0.7
sn3218              1.2.7
soupsieve           1.8
spidev              3.4
ssh-import-id       5.7
thonny              3.3.6
touchphat           0.0.1
twython             3.7.0
typed-ast           1.3.1
unicode-slugify     0.1.5
unicornhathd        0.0.4
Unidecode           1.3.2
urllib3             1.24.1
webencodings        0.5.1
Werkzeug            0.14.1
wheel               0.32.3
wrapt               1.10.11
pi@chris-pi:~ $ sudo pip3 install -U setuptools
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Collecting setuptools
  Downloading https://files.pythonhosted.org/packages/3b/02/8d4d27b1cacaac2d127d17a22d92a2a5eedcb7817d4ed8ab0d4daf5c4/setuptools-60.9.3-py3-none-any.whl (MB)
    100% |████████████████████████████████| 1.1MB 366kB/s
Installing collected packages: setuptools
  Found existing installation: setuptools 40.8.0
    Not uninstalling setuptools at /usr/lib/python3/dist-packages, outside enonment /usr
    Can't uninstall 'setuptools'. No files were found to uninstall.
Successfully installed setuptools-60.9.3
pi@chris-pi:~ $ sudo pip3 install -U django
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Collecting django
  Downloading https://files.pythonhosted.org/packages/9c/0e/02b7eff8fac2c25ed9933d4e899f6e6f283ae8eaf5189431057c8d406/Django-3.2.12-py3-none-any.whl (7.9M
    100% |████████████████████████████████| 7.9MB 57kB/s
Collecting sqlparse>=0.2.2 (from django)
  Downloading https://files.pythonhosted.org/packages/05/40/d836d55fb3f46724339ab7b814822fda522cd395fa41e282684e71ee5/sqlparse-0.4.2-py3-none-any.whl (42k
    100% |████████████████████████████████| 51kB 1.5MB/s
Collecting asgiref<4,>=3.3.2 (from django)
  Downloading https://files.pythonhosted.org/packages/0b/9f/5f3b91391578312821b669a0397d58535b4e82966c8f1667525c7d563/asgiref-3.5.0-py3-none-any.whl
Requirement already satisfied, skipping upgrade: pytz in /usr/local/lib/pytho7/dist-packages (from django) (2021.3)
Collecting typing-extensions; python_version < "3.8" (from asgiref<4,>=3.3.2-ango)
  Downloading https://files.pythonhosted.org/packages/45/6b/44f7f8f1e110027cf56b59f2fad776cca7e1704396d043f89effd3a0e/typing_extensions-4.1.1-py3-none-anyl
Installing collected packages: sqlparse, typing-extensions, asgiref, django
Successfully installed asgiref-3.5.0 django-3.2.12 sqlparse-0.4.2 typing-exteons-4.1.1
pi@chris-pi:~ $ sudo pip3 install -U django-filter
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Collecting django-filter
  Downloading https://files.pythonhosted.org/packages/37/90/8fbf530e14dbcaf5080078cbae9e4f805f20888973488ebe8480c3c28/django_filter-21.1-py3-none-any.whl kB)
    100% |████████████████████████████████| 81kB 1.5MB/s
Requirement already satisfied, skipping upgrade: Django>=2.2 in /usr/local/liython3.7/dist-packages (from django-filter) (3.2.12)
Requirement already satisfied, skipping upgrade: sqlparse>=0.2.2 in /usr/locaib/python3.7/dist-packages (from Django>=2.2->django-filter) (0.4.2)
Requirement already satisfied, skipping upgrade: pytz in /usr/local/lib/pytho7/dist-packages (from Django>=2.2->django-filter) (2021.3)
Requirement already satisfied, skipping upgrade: asgiref<4,>=3.3.2 in /usr/lo/lib/python3.7/dist-packages (from Django>=2.2->django-filter) (3.5.0)
Requirement already satisfied, skipping upgrade: typing-extensions; python_veon < "3.8" in /usr/local/lib/python3.7/dist-packages (from asgiref<4,>=3.3.2-ango>=2.2->django-filter) (4.1.1)
Installing collected packages: django-filter
Successfully installed django-filter-21.1
pi@chris-pi:~ $ sudo pip3 install -U requests
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Collecting requests
  Downloading https://files.pythonhosted.org/packages/2d/61/08076519c80041bc01a8af0cbd3bf3e2b62af10435d269a9d0f40564d/requests-2.27.1-py2.py3-none-any.whl3kB)
    100% |████████████████████████████████| 71kB 1.6MB/s
Collecting charset-normalizer~=2.0.0; python_version >= "3" (from requests)
  Downloading https://files.pythonhosted.org/packages/06/b3/24afc8868eba069a7650ac750a778862dc34941a4bebeb58706715726/charset_normalizer-2.0.12-py3-none-awhl
Requirement already satisfied, skipping upgrade: certifi>=2017.4.17 in /usr/lpython3/dist-packages (from requests) (2018.8.24)
Requirement already satisfied, skipping upgrade: idna<4,>=2.5; python_version "3" in /usr/lib/python3/dist-packages (from requests) (2.6)
Requirement already satisfied, skipping upgrade: urllib3<1.27,>=1.21.1 in /usib/python3/dist-packages (from requests) (1.24.1)
Installing collected packages: charset-normalizer, requests
  Found existing installation: requests 2.21.0
    Not uninstalling requests at /usr/lib/python3/dist-packages, outside enviment /usr
    Can't uninstall 'requests'. No files were found to uninstall.
Successfully installed charset-normalizer-2.0.12 requests-2.27.1
pi@chris-pi:~ $ sudo apt update
Get:1 http://archive.raspberrypi.org/debian buster InRelease [32.6 kB]
Get:2 http://archive.raspberrypi.org/debian buster/main armhf Packages [393 kB]
Get:3 http://raspbian.raspberrypi.org/raspbian buster InRelease [15.0 kB]
Get:4 http://raspbian.raspberrypi.org/raspbian buster/main armhf Packages [13.0 MB]
Fetched 13.5 MB in 17s (777 kB/s)
Reading package lists... Done
Building dependency tree
Reading state information... Done
152 packages can be upgraded. Run 'apt list --upgradable' to see them.
pi@chris-pi:~ $ sudo apt install mariadb-server mariadb-client
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following additional packages will be installed:
  galera-3 gawk libcgi-fast-perl libcgi-pm-perl libconfig-inifiles-perl
  libdbd-mysql-perl libdbi-perl libencode-locale-perl libfcgi-perl
  libhtml-parser-perl libhtml-tagset-perl libhtml-template-perl
  libhttp-date-perl libhttp-message-perl libio-html-perl
  liblwp-mediatypes-perl libreadline5 libsigsegv2 libterm-readkey-perl
  libtimedate-perl liburi-perl mariadb-client-10.3 mariadb-client-core-10.3
  mariadb-common mariadb-server-10.3 mariadb-server-core-10.3 socat
Suggested packages:
  gawk-doc libclone-perl libmldbm-perl libnet-daemon-perl
  libsql-statement-perl libdata-dump-perl libipc-sharedcache-perl
  libwww-perl mariadb-test tinyca
The following NEW packages will be installed:
  galera-3 gawk libcgi-fast-perl libcgi-pm-perl libconfig-inifiles-perl
  libdbd-mysql-perl libdbi-perl libencode-locale-perl libfcgi-perl
  libhtml-parser-perl libhtml-tagset-perl libhtml-template-perl
  libhttp-date-perl libhttp-message-perl libio-html-perl
  liblwp-mediatypes-perl libreadline5 libsigsegv2 libterm-readkey-perl
  libtimedate-perl liburi-perl mariadb-client mariadb-client-10.3
  mariadb-client-core-10.3 mariadb-server mariadb-server-10.3
  mariadb-server-core-10.3 socat
The following packages will be upgraded:
  mariadb-common
1 upgraded, 28 newly installed, 0 to remove and 151 not upgraded.
Need to get 18.2 MB of archives.
After this operation, 150 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://raspbian.mirror.constant.com/raspbian buster/main armhf libsigsegv2 armhf 2.12-2 [32.3 kB]
Get:2 http://raspbian.mirror.constant.com/raspbian buster/main armhf gawk armhf 1:4.2.1+dfsg-1 [590 kB]
Get:3 http://raspbian.mirror.constant.com/raspbian buster/main armhf mariadb-common all 1:10.3.31-0+deb10u1 [32.7 kB]
Get:4 http://raspbian.mirror.constant.com/raspbian buster/main armhf galera-3 armhf 25.3.25-2 [811 kB]
Get:5 http://raspbian.mirror.constant.com/raspbian buster/main armhf libdbi-perl armhf 1.642-1+deb10u2 [767 kB]
Get:6 http://raspbian.mirror.constant.com/raspbian buster/main armhf libconfig-inifiles-perl all 3.000001-1 [51.9 kB]
Get:7 http://raspbian.mirror.constant.com/raspbian buster/main armhf libreadline5 armhf 5.2+dfsg-3 [103 kB]
Get:8 http://raspbian.mirror.constant.com/raspbian buster/main armhf mariadb-client-core-10.3 armhf 1:10.3.31-0+deb10u1 [4,731 kB]
Get:9 http://raspbian.mirror.constant.com/raspbian buster/main armhf mariadb-client-10.3 armhf 1:10.3.31-0+deb10u1 [989 kB]
Get:10 http://raspbian.mirror.constant.com/raspbian buster/main armhf mariadb-server-core-10.3 armhf 1:10.3.31-0+deb10u1 [5,230 kB]
Get:11 http://raspbian.mirror.constant.com/raspbian buster/main armhf socat armhf 1.7.3.2-2 [324 kB]
Get:12 http://raspbian.mirror.constant.com/raspbian buster/main armhf mariadb-server-10.3 armhf 1:10.3.31-0+deb10u1 [3,567 kB]
Get:13 http://raspbian.mirror.constant.com/raspbian buster/main armhf libhtml-tagset-perl all 3.20-3 [12.7 kB]
Get:14 http://raspbian.mirror.constant.com/raspbian buster/main armhf liburi-perl all 1.76-1 [89.9 kB]
Get:15 http://raspbian.mirror.constant.com/raspbian buster/main armhf libhtml-parser-perl armhf 3.72-3+b2 [101 kB]
Get:16 http://raspbian.mirror.constant.com/raspbian buster/main armhf libcgi-pm-perl all 4.40-1 [222 kB]
Get:17 http://raspbian.mirror.constant.com/raspbian buster/main armhf libfcgi-perl armhf 0.78-2+b2 [35.0 kB]
Get:18 http://raspbian.mirror.constant.com/raspbian buster/main armhf libcgi-fast-perl all 1:2.13-1 [11.4 kB]
Get:19 http://raspbian.mirror.constant.com/raspbian buster/main armhf libdbd-mysql-perl armhf 4.050-2 [114 kB]
Get:20 http://raspbian.mirror.constant.com/raspbian buster/main armhf libencode-locale-perl all 1.05-1 [13.7 kB]
Get:21 http://raspbian.mirror.constant.com/raspbian buster/main armhf libhtml-template-perl all 2.97-1 [66.0 kB]
Get:22 http://raspbian.mirror.constant.com/raspbian buster/main armhf libtimedate-perl all 2.3000-2+deb10u1 [38.1 kB]
Get:23 http://raspbian.mirror.constant.com/raspbian buster/main armhf libhttp-date-perl all 6.02-1 [10.7 kB]
Get:24 http://raspbian.mirror.constant.com/raspbian buster/main armhf libio-html-perl all 1.001-1 [17.6 kB]
Get:25 http://raspbian.mirror.constant.com/raspbian buster/main armhf liblwp-mediatypes-perl all 6.02-1 [22.1 kB]
Get:26 http://raspbian.mirror.constant.com/raspbian buster/main armhf libhttp-message-perl all 6.18-1 [77.8 kB]
Get:27 http://raspbian.mirror.constant.com/raspbian buster/main armhf libterm-readkey-perl armhf 2.38-1 [26.3 kB]
Get:28 http://raspbian.mirror.constant.com/raspbian buster/main armhf mariadb-client all 1:10.3.31-0+deb10u1 [31.5 kB]
Get:29 http://raspbian.mirror.constant.com/raspbian buster/main armhf mariadb-server all 1:10.3.31-0+deb10u1 [31.7 kB]
Fetched 18.2 MB in 10s (1,847 kB/s)
Reading changelogs... Done
Preconfiguring packages ...
Selecting previously unselected package libsigsegv2:armhf.
(Reading database ... 104994 files and directories currently installed.)
Preparing to unpack .../libsigsegv2_2.12-2_armhf.deb ...
Unpacking libsigsegv2:armhf (2.12-2) ...
Setting up libsigsegv2:armhf (2.12-2) ...
Selecting previously unselected package gawk.
(Reading database ... 105003 files and directories currently installed.)
Preparing to unpack .../0-gawk_1%3a4.2.1+dfsg-1_armhf.deb ...
Unpacking gawk (1:4.2.1+dfsg-1) ...
Preparing to unpack .../1-mariadb-common_1%3a10.3.31-0+deb10u1_all.deb ...
Unpacking mariadb-common (1:10.3.31-0+deb10u1) over (1:10.3.27-0+deb10u1) ...
Selecting previously unselected package galera-3.
Preparing to unpack .../2-galera-3_25.3.25-2_armhf.deb ...
Unpacking galera-3 (25.3.25-2) ...
Selecting previously unselected package libdbi-perl:armhf.
Preparing to unpack .../3-libdbi-perl_1.642-1+deb10u2_armhf.deb ...
Unpacking libdbi-perl:armhf (1.642-1+deb10u2) ...
Selecting previously unselected package libconfig-inifiles-perl.
Preparing to unpack .../4-libconfig-inifiles-perl_3.000001-1_all.deb ...
Unpacking libconfig-inifiles-perl (3.000001-1) ...
Selecting previously unselected package libreadline5:armhf.
Preparing to unpack .../5-libreadline5_5.2+dfsg-3_armhf.deb ...
Unpacking libreadline5:armhf (5.2+dfsg-3) ...
Selecting previously unselected package mariadb-client-core-10.3.
Preparing to unpack .../6-mariadb-client-core-10.3_1%3a10.3.31-0+deb10u1_armhf.deb ...
Unpacking mariadb-client-core-10.3 (1:10.3.31-0+deb10u1) ...
Selecting previously unselected package mariadb-client-10.3.
Preparing to unpack .../7-mariadb-client-10.3_1%3a10.3.31-0+deb10u1_armhf.deb ...
Unpacking mariadb-client-10.3 (1:10.3.31-0+deb10u1) ...
Selecting previously unselected package mariadb-server-core-10.3.
Preparing to unpack .../8-mariadb-server-core-10.3_1%3a10.3.31-0+deb10u1_armhf.deb ...
Unpacking mariadb-server-core-10.3 (1:10.3.31-0+deb10u1) ...
Selecting previously unselected package socat.
Preparing to unpack .../9-socat_1.7.3.2-2_armhf.deb ...
Unpacking socat (1.7.3.2-2) ...
Setting up mariadb-common (1:10.3.31-0+deb10u1) ...
Selecting previously unselected package mariadb-server-10.3.
(Reading database ... 105548 files and directories currently installed.)
Preparing to unpack .../00-mariadb-server-10.3_1%3a10.3.31-0+deb10u1_armhf.deb ...
Unpacking mariadb-server-10.3 (1:10.3.31-0+deb10u1) ...
Selecting previously unselected package libhtml-tagset-perl.
Preparing to unpack .../01-libhtml-tagset-perl_3.20-3_all.deb ...
Unpacking libhtml-tagset-perl (3.20-3) ...
Selecting previously unselected package liburi-perl.
Preparing to unpack .../02-liburi-perl_1.76-1_all.deb ...
Unpacking liburi-perl (1.76-1) ...
Selecting previously unselected package libhtml-parser-perl.
Preparing to unpack .../03-libhtml-parser-perl_3.72-3+b2_armhf.deb ...
Unpacking libhtml-parser-perl (3.72-3+b2) ...
Selecting previously unselected package libcgi-pm-perl.
Preparing to unpack .../04-libcgi-pm-perl_4.40-1_all.deb ...
Unpacking libcgi-pm-perl (4.40-1) ...
Selecting previously unselected package libfcgi-perl.
Preparing to unpack .../05-libfcgi-perl_0.78-2+b2_armhf.deb ...
Unpacking libfcgi-perl (0.78-2+b2) ...
Selecting previously unselected package libcgi-fast-perl.
Preparing to unpack .../06-libcgi-fast-perl_1%3a2.13-1_all.deb ...
Unpacking libcgi-fast-perl (1:2.13-1) ...
Selecting previously unselected package libdbd-mysql-perl:armhf.
Preparing to unpack .../07-libdbd-mysql-perl_4.050-2_armhf.deb ...
Unpacking libdbd-mysql-perl:armhf (4.050-2) ...
Selecting previously unselected package libencode-locale-perl.
Preparing to unpack .../08-libencode-locale-perl_1.05-1_all.deb ...
Unpacking libencode-locale-perl (1.05-1) ...
Selecting previously unselected package libhtml-template-perl.
Preparing to unpack .../09-libhtml-template-perl_2.97-1_all.deb ...
Unpacking libhtml-template-perl (2.97-1) ...
Selecting previously unselected package libtimedate-perl.
Preparing to unpack .../10-libtimedate-perl_2.3000-2+deb10u1_all.deb ...
Unpacking libtimedate-perl (2.3000-2+deb10u1) ...
Selecting previously unselected package libhttp-date-perl.
Preparing to unpack .../11-libhttp-date-perl_6.02-1_all.deb ...
Unpacking libhttp-date-perl (6.02-1) ...
Selecting previously unselected package libio-html-perl.
Preparing to unpack .../12-libio-html-perl_1.001-1_all.deb ...
Unpacking libio-html-perl (1.001-1) ...
Selecting previously unselected package liblwp-mediatypes-perl.
Preparing to unpack .../13-liblwp-mediatypes-perl_6.02-1_all.deb ...
Unpacking liblwp-mediatypes-perl (6.02-1) ...
Selecting previously unselected package libhttp-message-perl.
Preparing to unpack .../14-libhttp-message-perl_6.18-1_all.deb ...
Unpacking libhttp-message-perl (6.18-1) ...
Selecting previously unselected package libterm-readkey-perl.
Preparing to unpack .../15-libterm-readkey-perl_2.38-1_armhf.deb ...
Unpacking libterm-readkey-perl (2.38-1) ...
Selecting previously unselected package mariadb-client.
Preparing to unpack .../16-mariadb-client_1%3a10.3.31-0+deb10u1_all.deb ...
Unpacking mariadb-client (1:10.3.31-0+deb10u1) ...
Selecting previously unselected package mariadb-server.
Preparing to unpack .../17-mariadb-server_1%3a10.3.31-0+deb10u1_all.deb ...
Unpacking mariadb-server (1:10.3.31-0+deb10u1) ...
Setting up libconfig-inifiles-perl (3.000001-1) ...
Setting up libreadline5:armhf (5.2+dfsg-3) ...
Setting up gawk (1:4.2.1+dfsg-1) ...
Setting up libhtml-tagset-perl (3.20-3) ...
Setting up liblwp-mediatypes-perl (6.02-1) ...
Setting up libencode-locale-perl (1.05-1) ...
Setting up socat (1.7.3.2-2) ...
Setting up mariadb-server-core-10.3 (1:10.3.31-0+deb10u1) ...
Setting up libio-html-perl (1.001-1) ...
Setting up galera-3 (25.3.25-2) ...
Setting up libtimedate-perl (2.3000-2+deb10u1) ...
Setting up mariadb-client-core-10.3 (1:10.3.31-0+deb10u1) ...
Setting up libfcgi-perl (0.78-2+b2) ...
Setting up libterm-readkey-perl (2.38-1) ...
Setting up liburi-perl (1.76-1) ...
Setting up libdbi-perl:armhf (1.642-1+deb10u2) ...
Setting up libhttp-date-perl (6.02-1) ...
Setting up mariadb-client-10.3 (1:10.3.31-0+deb10u1) ...
Setting up libdbd-mysql-perl:armhf (4.050-2) ...
Setting up libhtml-parser-perl (3.72-3+b2) ...
Setting up mariadb-server-10.3 (1:10.3.31-0+deb10u1) ...
Created symlink /etc/systemd/system/mysql.service → /lib/systemd/system/mariadb.service.
Created symlink /etc/systemd/system/mysqld.service → /lib/systemd/system/mariadb.service.
Created symlink /etc/systemd/system/multi-user.target.wants/mariadb.service → /lib/systemd/system/mariadb.service.
Setting up libhttp-message-perl (6.18-1) ...
Setting up mariadb-client (1:10.3.31-0+deb10u1) ...
Setting up libcgi-pm-perl (4.40-1) ...
Setting up libhtml-template-perl (2.97-1) ...
Setting up mariadb-server (1:10.3.31-0+deb10u1) ...
Setting up libcgi-fast-perl (1:2.13-1) ...
Processing triggers for systemd (241-7~deb10u7+rpi1) ...
Processing triggers for man-db (2.8.5-2) ...
Processing triggers for libc-bin (2.28-10+rpi1) ...
pi@chris-pi:~ $ sudo apt install python3-mysqldb
Reading package lists... Done
Building dependency tree
Reading state information... Done
Suggested packages:
  python-egenix-mxdatetime python3-mysqldb-dbg
The following NEW packages will be installed:
  python3-mysqldb
0 upgraded, 1 newly installed, 0 to remove and 151 not upgraded.
Need to get 53.1 kB of archives.
After this operation, 177 kB of additional disk space will be used.
Get:1 http://raspbian.mirror.constant.com/raspbian buster/main armhf python3-mysqldb armhf 1.3.10-2+b1 [53.1 kB]
Fetched 53.1 kB in 1s (54.9 kB/s)
Selecting previously unselected package python3-mysqldb.
(Reading database ... 105989 files and directories currently installed.)
Preparing to unpack .../python3-mysqldb_1.3.10-2+b1_armhf.deb ...
Unpacking python3-mysqldb (1.3.10-2+b1) ...
Setting up python3-mysqldb (1.3.10-2+b1) ...
pi@chris-pi:~ $ sudo pip3 install -U mysqlclient
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Collecting mysqlclient
  Downloading https://www.piwheels.org/simple/mysqlclient/mysqlclient-2.1.0-cp37-cp37m-linux_armv7l.whl (107kB)
    100% |████████████████████████████████| 112kB 444kB/s
Installing collected packages: mysqlclient
  Found existing installation: mysqlclient 1.3.10
    Not uninstalling mysqlclient at /usr/lib/python3/dist-packages, outside environment /usr
    Can't uninstall 'mysqlclient'. No files were found to uninstall.
Successfully installed mysqlclient-2.1.0
pi@chris-pi:~ $ sudo mysql_secure_installation

NOTE: RUNNING ALL PARTS OF THIS SCRIPT IS RECOMMENDED FOR ALL MariaDB
      SERVERS IN PRODUCTION USE!  PLEASE READ EACH STEP CAREFULLY!

In order to log into MariaDB to secure it, we'll need the current
password for the root user.  If you've just installed MariaDB, and
you haven't set the root password yet, the password will be blank,
so you should just press enter here.

Enter current password for root (enter for none):
OK, successfully used password, moving on...

Setting the root password ensures that nobody can log into the MariaDB
root user without the proper authorisation.

Set root password? [Y/n] Y
New password:
Re-enter new password:
Password updated successfully!
Reloading privilege tables..
 ... Success!


By default, a MariaDB installation has an anonymous user, allowing anyone
to log into MariaDB without having to have a user account created for
them.  This is intended only for testing, and to make the installation
go a bit smoother.  You should remove them before moving into a
production environment.

Remove anonymous users? [Y/n] Y
 ... Success!

Normally, root should only be allowed to connect from 'localhost'.  This
ensures that someone cannot guess at the root password from the network.

Disallow root login remotely? [Y/n] Y
 ... Success!

By default, MariaDB comes with a database named 'test' that anyone can
access.  This is also intended only for testing, and should be removed
before moving into a production environment.

Remove test database and access to it? [Y/n] Y
 - Dropping test database...
 ... Success!
 - Removing privileges on test database...
 ... Success!

Reloading the privilege tables will ensure that all changes made so far
will take effect immediately.

Reload privilege tables now? [Y/n] Y
 ... Success!

Cleaning up...

All done!  If you've completed all of the above steps, your MariaDB
installation should now be secure.

Thanks for using MariaDB!
pi@chris-pi:~ $
```

