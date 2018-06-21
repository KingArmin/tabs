# Tabchi V18


</h4>
<pre>
<span>sudo apt-get update; sudo apt-get upgrade; sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev; sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv;
</span>
</pre>
<hr>

* * *

# Install

```sh
git clone https://github.com/KingArmin/tabs
cd tabs
chmod +x install.sh
./install.sh

```
* * *
## Create BOT [Auto]
```
cd tabs
lua creator.lua

screen ./tabchi-0.sh

```
## Create BOT [Menual]

```sh
cd tabs
lua manual-creator.lua

screen ./tabchi-[NUM].sh

```
* * *
## AutoLaunch
```sh

cd tabs
killall tmux
killall bash
killall nohup
killall screen
./anticrash.sh


```
***
