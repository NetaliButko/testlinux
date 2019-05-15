# testlinux
1)
$sodo 
2)
alias way='/home/user/Documents/Project'
3)

4)
sudo update-java-alternatives --list
sudo update-java-alternatives --set /usr/lib/jvm/java-1.10.0-openjdk-amd64

5)
docker start 6477a77b7596    //пуск контейнера убунты
docker rm  6477a77b7596       //удаление  контейнера
или docker run --rm -it ubuntu:14.04 /bin/bash         //Запустить контейнер и автоматически удалить его после того как он остановится 
6)
docker ps                     //проверка запущенных контейнеров
7)
 lsb_release -a    //позволяет узнать о ОС из терминала убунты
 
