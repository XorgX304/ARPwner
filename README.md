Installation
-----------
apt-get install python-pypcap

SSLstrip
----------
you have to setup the iptables to redirect http traffic to sslstrip
iptables -t nat -A PREROUTING -p tcp --destination-port 80 -j REDIRECT --to-port 1337