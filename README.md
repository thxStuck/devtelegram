# devtelegram

<h2>Шаг 1: Установка OpenSSH-сервера</h2> <h3>Введите команду:</h3> sudo apt update <li><p>Затем установите OpenSSH-сервер:</p></li> sudo apt install openssh-server <p><li>Запустите службу OpenSSH:</li></p><li> sudo systemctl start sshd </li><p>Проверьте статус службы OpenSSH:</p> sudo systemctl status sshd <h2>Шаг 2: Установка Docker</h2> <ul> <li>Установите необходимые пакеты:</li> sudo apt install apt-transport-https ca-certificates curl software-properties-common <li>Добавьте ключ репозитория Docker:</li> curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - <li>Добавьте репозиторий Docker:</li> sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" <li>Обновите список пакетов:</li> sudo apt update <li>Установите Docker:</li> sudo apt install docker-ce </ul> <h2>Шаг 3: Установка Python</h2> <ul> <li>Установите Python:</li> sudo apt install python3 <li>Установите pip (менеджер пакетов Python):</li> sudo apt install python3-pip </ul> <h2>Шаг 4: Подготовка к запуску Docker Compose</h2> <ul> <li>Перед запуском команды <code>sudo docker compose up --build Ubuntu</code>, убедитесь, что:</li> <ul> <li>Вы находитесь в директории, где находится файл <code>docker-compose.yml</code></li> <li>Выполните команду: <code>sudo docker compose up --build Ubuntu</code></li> </ul> </ul>


sudo docker compose up --build
Ubuntu



