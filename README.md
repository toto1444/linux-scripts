# linux-scripts

echo cd root && cd /root && wget https://raw.githubusercontent.com/toto1444/linux-scripts/master/add-apt-repository.sh && cp /root/add-apt-repository.sh /usr/sbin/add-apt-repository && chmod o+x /usr/sbin/add-apt-repository && chown root:root /usr/sbin/add-apt-repository && echo repository add..... && add-apt-repository ppa:elementary-os/daily && echo . && echo apt update && echo . && apt-get update && echo . && echo apt install nimf! && echo . && apt-get install nimf -y && im-config -n nimf && echo remove repository && rm /etc/apt/sources.list.d/elementary* && apt-get update
