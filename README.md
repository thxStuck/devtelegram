# devtelegram


Шаг 1: Установка OpenSSH-сервера
Введите команду: sudo apt update
Затем установите OpenSSH-сервер: sudo apt install openssh-server
Запустите службу OpenSSH: sudo systemctl start sshd
Проверьте статус службы OpenSSH: sudo systemctl status sshd
Шаг 2: Установка Docker
Установите необходимые пакеты: sudo apt install apt-transport-https ca-certificates curl software-properties-common
Добавьте ключ репозитория Docker: curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
Добавьте репозиторий Docker: sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
Обновите список пакетов: sudo apt update
Установите Docker: sudo apt install docker-ce
Шаг 3: Установка Python
Установите Python: sudo apt install python3
Установите pip (менеджер пакетов Python): sudo apt install python3-pip
Шаг 4: Подготовка к запуску Docker Compose
Перед запуском команды sudo docker compose up --build Ubuntu, убедитесь, что:
Вы находитесь в директории, где находится файл docker-compose.yml
sudo docker compose up --build
Ubuntu



