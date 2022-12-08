# Minecraft
### Run function
```bash
function mine {
	cd Documents/git/Minecraft/;
	git pull;
	cp -r main/ ~/Games/mine/server/world/;
	cd ~/Games/mine/;
	java -jar TLauncher-2.86.jar; 
	cd server/;
	java -Xmx1024M -Xms1024M -jar server.jar nogui;
};
```
