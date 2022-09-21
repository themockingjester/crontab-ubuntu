## Basic structure of crontab to run a nodejs file at regular interval
```
# m h  dom mon dow   command
PATH=/bin:/usr/bin:/usr/local/bin:/home/ubuntu/.nvm/versions/node/v16.13.1/bin

* * * * * cd /home/ubuntu/project/crons && node fileToRun.js >> /tmp/loggingFile.txt
```
