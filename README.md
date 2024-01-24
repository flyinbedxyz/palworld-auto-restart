# palworld-auto-restart
a script to monitor memory usage and auto restart server of palworld(and auto backup)
Recommended to use with crontab:
crontab -e
* * * * * /bin/bash /home/ubuntu/auto_reboot.sh

一个给linux的palworld服务器设计的脚本，根据内存占用判断是否重启服务端，具体参数可设置，在重启的时候会自动备份存档，推荐结合crontab一起使用，例如每分钟执行一次这个脚本：
crontab -e
* * * * * /bin/bash /home/ubuntu/auto_reboot.sh
