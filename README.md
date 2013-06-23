haproxy-remote
==============

Simple init script that exposes the haproxy command socket over TCP using socat.

Install socat: `sudo apt-get install socat`

Copy the contents of etc/ in to the respective locations on your filesystem.

Launch with: `sudo /etc/init.d/haproxy-remote start`

Set to run on boot with: `sudo update-rc.d haproxy-remote defaults`

Done to complement using hatop remotely over TCP: https://github.com/Wirehive/hatop
