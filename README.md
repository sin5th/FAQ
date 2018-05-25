# FAQ
Troubleshooting


# program gone 进程挂掉
### oom
```
sudo dmesg |grep -i kill
```
```bash
# systime_human.sh
ut=`cut -d' ' -f1 </proc/uptime`
ts=`date +%s`
date -d"70-1-1 + $ts sec - $ut sec + $1 sec" +"%F %T"
```

