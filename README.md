## Configuration Step's
```
1. Choose an image -> Ubuntu 18.04 LTS
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
15. Install Tomcat using below step's
16. Go to <ip>/manager/html
17. Enter username and password as admin
18. Add 	<packaging>war</packaging> to pom.xml inside spring boot application
19. Right click on project > Run As > Maven Install
20. war file will be generated inside target directory
21. Go to <ip>:8081
```

## Tomact 8.5 Installation

```
git clone https://gist.github.com/SaiAshish9/5ec3dec5810ea50192578018d18673cd
cd 5ec3dec5810ea50192578018d18673cd
chmod +x tomcat-setup.sh
./tomcat-setup.sh
```



## Reference Links

```
http://youtube.com/watch?v=sLyxKcO37HY
```
