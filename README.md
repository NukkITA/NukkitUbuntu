# Guida per installare Nukkit su ubuntu.

## Installazione JAVA
sudo apt-add-repository ppa:webupd8team/java

sudo apt-get update

sudo apt-get install oracle-java8-installer

java -version

## Installazione NUKKIT

wget https://ci.nukkitx.com/job/NukkitX/job/Nukkit/job/master/lastSuccessfulBuild/artifact/

Crea un'eseguibile (start.sh)

Modifica il file e metti questa stringa:

java -jar nukkit-1.0-SNAPSHOT.jar

### Se si vuole mettere un massimo di ram e un minimo:

java -Xmx2048M -Xms1024M -jar nukkit-1.0-SNAPSHOT.jar	(i numeri sono personalizzabili, 1024M: 1GB di RAM)

chmod +x ./start.sh

./start.sh (Così avrete avviato nukkit!)
