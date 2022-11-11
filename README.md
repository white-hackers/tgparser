🧾Автор спамера форум SLIVATOR.COM
===================================
Телеграмм спамер, Инвайтинг и Парсер
===================================
<p align="center">
  <img src="https://i.imgur.com/5KZlpj5.png">
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
