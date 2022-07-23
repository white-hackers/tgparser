🧾Автор спамера форум TUT.GURU
===================================
Телеграмм спамер, Инвайтинг и Парсер
===================================
<p align="center">
  <img src="https://downloader.disk.yandex.ru/preview/6c0c0c755828a2fa96aad64da3be3e5e84b275db7d9ab8c9b436ad39635a7bb2/62dc4955/5AF-szxvAniyOQi7Mg4djjcRclevLxS8Gi_2nqAfzp8juIrR7iskid2K283Iz_GPNXquCkoo2nuEQ0NSMba7dQ%3D%3D?uid=0&filename=68747470733a2f2f692e696d6775722e636f6d2f704b5530694f322e706e67.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=0&tknv=v2&size=2048x2048">
</p>

# Установка
* Windows:
  * Download Python 3.8 [here](https://www.python.org/downloads/release/python-38) 
  * Launch installer, click 'add python to PATH'
  * Download **tgparser**
  * Open Command Line in **tgparser directory**
  * Run command: ***python setup.py -i**`
  * Then go to [my.telegram.org] and login in your account
  * Choose API Development Tools
  * In Command Line run ***python setup.py -c***
  * Enter api_id, api_hash and phone number
  
* Termux:
  * `pkg update`
  * `pkg install python3 python3-pip git -y`
  * `git clone https://github.com/white-hackers/tgparser/`
  * `cd tgparser`
  * `python setup.py -i`
  * `Then go to [my.telegram.org] and login in your account`
  * `Choose API Development Tools`
  * `python setup.py -c`
  * `Enter api_id, api_hash and phone number`
* Linux
  * `sudo apt update`
  * `sudo apt install python3 python3-pip git -y`
  * `git clone https://github.com/white-hackers/tgparser/`
  * `cd tgparser`
  * `python setup.py -i`
  * `Then go to [my.telegram.org] and login in your account`
  * `Choose API Development Tools`
  * `In Command Line run ***python setup.py -c***`
  * `Enter api_id, api_hash and phone number`

# Запуск
* Парсинг самый первый. 
  * `python pars.py`
* Инвайтинг 
  * `python invite.py members.csv`
* Спамер
  * `python smsbot.py members.csv`
