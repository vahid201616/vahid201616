- 👋 Hi, I’m @vahid201616
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
vahid201616/vahid201616 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

ubontu 20

apt update && apt upgrade -y
apt install curl socat -y

change port 
vi /etc/ssh/sshd_config
Port 2222
then
systemctl restart ssh
Or
reboot
Test
netstat –nltp | grep ssh
------------------------------------------------------------
sanaee normal
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)

sanaee custom
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh) v1.7.9

SSL
apt-get install certbot -y
certbot certonly --standalone --agree-tos --register-unsafely-without-email -d yourdomain.com
certbot renew --dry-run
--------------------------------------------------------------
