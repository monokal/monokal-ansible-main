# ansible-main
git clone --recursive https://github.com/monokal/monokal-ansible-main.git && \
cd monokal-ansible-main && \
git submodule update --init --recursive && \
git submodule foreach git pull origin master
