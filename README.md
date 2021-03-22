## Configuration Step's
```
1. Choose an image -> Ubuntu 20.04 LTS
2. Choose a plan -> Basic
3. CPU Option's -> Regular Intel -> $5/mo
4. Authentication -> Password (Create root password) (say XYZ)
5. Resources -> Droplet(1) -> ... -> Access Console
6. login -> 
7. username : root , password : XYZ
8. Enter Password : XYZ
9. sudo apt update
10. sudo apt upgrade
11. Install the package maintainer's version
12. exit
13. 9. Connect via terminal
14.  sudo ssh root@<ip> 
15. sudo apt install openjdk-11-jdk-headless
16. java -version
```

## Tomact 8.5 Installation

```
sudo apt-get update
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
sudo apt-get install tomact8 tomact8-docs tomcat8-admin tomcat8-examples
service tomcat8 stop
service tomcat8 start
service tomcat8 restart
```


## Reference Links

```
http://youtube.com/watch?v=sLyxKcO37HY
```
