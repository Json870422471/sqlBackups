# sqlBackups
mysql备份 docker安装的mysql 备份

crontab -e

#每天凌晨3点全量备份mysql,并且把sql备份文件同步到备份服务器上。异地容灾，有备无患！

0 3 * * * /root/mysql_backup.sh
