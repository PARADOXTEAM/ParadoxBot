
* * *

# Installation

```sh

sudo apt-get update

sudo apt-get upgrade

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev

# Let's install the bot.

cd $HOME

git clone https://github.com/PARADOXTEAM/ParadoxBot.git

cd ParadoxBot

chmod +x launch.sh

./launch.sh install

cd .luarocks && cd bin && ./luarocks-5.2 install luafilesystem && ./luarocks-5.2 install lub && ./luarocks-5.2 install luaexpat

cd $HOME

cd ParadoxBot

./launch.sh install

./launch.sh # Enter a phone number & confirmation code.

```
# AutoLaunch

```sh
sudo apt-get install tmux
----------------------------
killall screen
killall tmux
killall telegram-cli
tmux new-session -s script "bash steady.sh -t"

```

```sh
 sudo_users = {
    785830210,
    0,
    YourID
  }
```
Then restart the bot.


* * *

### Support and development

https://telegram.me/Paradox_TEAM
