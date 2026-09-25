Comandos para iniciar:
/workspaces/Minecraft-server/minecraft/run_crafty.sh

sudo pkill -f playitd 2>/dev/null
sudo /usr/bin/playitd > /tmp/playitd.log 2>&1 &
sleep 2
playit
