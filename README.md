1) Зарегистрироваться на GitHub
2) Отправить свой login от GitHub на почту bastan.r7@gmail.com
3) Ждать предложения стать членом FabLabInfo на свою почту
4)Сгенерить SSH ключ https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/
5)Скопировать ключ из файла id_rsa.pub в настройки(settings) на GitHub(SSh and GPG keys)
6)Выполнитьб комнаду :
				ssh-add ~/.ssh/id_rsa
где ~ - путь к папке .ssh
7)Скачать репозиторий android-BluetoothChat(назвние уточнить):
	a)Clone or download > Use SSH > копировать адрес > команда:
				git clone адрес
8)Имортировать скачанный проект в AndroidStudio(закройте все текущие прокеты(Close project) > Import project)
9)Через терминал в папке проекта выполнить проекта:
				git status
10)Создать в папке проекта файл .gitignore
11)Записать в файл имена файлов, выведенных в ответ на git status
12)...
