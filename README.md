# supervisor-notes

#### ubuntu

- install supervisor : `apt install supervisor`
- cd to `etc/supervisor/conf.d` and create new file eg : `email-worker.conf`
- nano `email-worker.conf` and paste the snippet :

### supervisor command

- `supervisorctl reread`
- `supervisorctl update`
- `supervisorctl start all`
- show supervisor status : `service supervisor status`
- stop supervisor : `service supervisor stop`
