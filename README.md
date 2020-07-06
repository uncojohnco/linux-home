# linux-home

- https://github.com/Bash-it/bash-it
- https://direnv.net/

---

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
