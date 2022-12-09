# Minecraft
### Run function
```bash
function mine {
	cd ~/Documents/git/Minecraft/;
	git pull;
	cp -rf world/ ~/Games/mine/server/world/;
	cd ~/Games/mine/;
	java -jar TLauncher-2.86.jar; 
	cd server/;
	java -Xmx1024M -Xms1024M -jar server.jar nogui;
	cp -rf world/ ~/Documents/git/Minecraft/world;
	cd ~/Documents/git/Minecraft/;
	git add world;
	git commit -m "update world";
	git push;
};
```
