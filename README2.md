#HOSTING OWN SERVER

check if behind nat with tracert ---- && traceroute -4 122.161.66.248

change port forwarding and (access contorl allow ssh on WAN)


follow https://dev.to/lloyds-digital/how-you-can-host-websites-from-home-4pke

<br>sudo apt-get install ssh
<br>sudo ufw allow OpenSSH
<br>sudo ufw enable
<br>ssh z@192.168.1.14
<br>ssh z@external_ip

getent group sudo
sudo deluser --remove-home parth
sudo ufw delete 1
