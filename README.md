🧾Автор спамера форум TUT.GURU
===================================
Телеграмм спамер, Инвайтинг и Парсер
===================================
<p align="center">
  <img src="https://downloader.disk.yandex.ru/preview/3db5a833c9f62f1b023068fd05a262fa4d003ef3c56b36e2a46cbd5058a5af2e/62dc4996/-CXPk9wu71UydjuR3lfXlqU1LTijes56jzgDO_naMLOE9PEMySNMI3xYHd7YGiFcEetampc216jnwljEpbKfrg%3D%3D?uid=0&filename=TET.jpg&disposition=inline&hash=&limit=0&content_type=image%2Fjpeg&owner_uid=0&tknv=v2&size=2048x2048">
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
