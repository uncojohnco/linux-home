# linux-home

- https://github.com/Bash-it/bash-it
- https://direnv.net/

centralize-bash-history
- https://stackify.com/syslog-101/
- https://www.elastic.co/guide/en/logstash/current/installing-logstash.html
- https://www.elastic.co/guide/en/logstash/7.8/running-logstash.html
- https://dzone.com/articles/centralize-bash-history

---


## Clean install
```bash
# install bash-it
git clone --depth=1 https://github.com/Bash-it/bash-it.git ~/.bash_it && \
~/.bash_it/install.sh && \
source ~/.bashrc && \
bash-it enable completion all && \

```

.inputrc
```bash
"\e[A": history-search-backward
"\e[B": history-search-forward
```
