get https://valtman.name/files/telegram-cli-1222 ; mv telegram-cli-1222 tg

sudo apt-get update

chmod +x launch.sh ; chmod +x tg

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
cd luarocks-2.2.2

./configure; sudo make bootstrap

sudo luarocks install serpent

sudo luarocks install redis-lua

sudo apt-get install lua-socket lua-sec

sudo apt-get install software-properties-common python-software-properties

sudo add-apt-repository ppa:ubuntu-toolchain-r/test

sudo apt update

sudo apt install gcc-6

cd ..

./launch.sh
