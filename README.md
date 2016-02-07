# ubuntu
cosas relacionadas con mi incursión en ubuntu  
***
**Instalar JRE y JDK 8**  
`sudo add-apt-repository ppa:webupd8team/java`  
`sudo apt-get update`  
`sudo apt-get install oracle-java8-installer`  

**Verificar la version instalada de Java**  
`java -version`  

**Colocar JRE Y JDK 8 por default**  
`sudo apt-get install oracle-java8-set-default`  
***
**Instalar Pycharm**  
`sudo add-apt-repository ppa:mystic-mirage/pycharm`  
`sudo apt-get update`  

**Version Pro**  
`sudo apt-get install pycharm`  
**Desinstalar Pro**  
`sudo apt-get remove pycharm`  

**Version Community**  
`sudo apt-get install pycharm-community`  
**Desinstalar Community**  
`sudo apt-get remove pycharm-community`  

**Remover el repositorio**  
`sudo add-apt-repository --remove ppa:mystic-mirage/pycharm`  
***
**Instalar servidor Apache**  
`sudo apt-get install apache2`  
**Instalar modulo mod_wsgi (para desplegar django con python 3)**  
`sudo apt-get install libapache2-mod-wsgi-py3`  
**Reiniciar Apache**  
`sudo /etc/init.d/apache2 restart`  
**Checar funcionamiento del servicio**  
`sudo systemctl status apache2.service`  
***
**Instalar PIP (python3)**  
`sudo apt-get install python3-pip`  
***
**Apagar el sistema**  
`sudo shutdown -h`  
