# Credits: https://t.me/tcpsyn (Space) | https://ssn.sellix.io

# SSN Proxy Tutorial

Thank you for your trust in SSN, you will not regret it.

# Suggested specs and details

Operating System: `Ubuntu 20.04`
Ram: `8 Gb`
CPU: `4 core` @ `1 Ghz`
Storage: `3 Gb`

# How To Setup SSN Proxy

# Before we begin, you will want to disable your IPV6 address on your server by running the following 3 commands:

sudo sysctl -w net.ipv6.conf.all.disable_ipv6=1
sudo sysctl -w net.ipv6.conf.default.disable_ipv6=1
sudo sysctl -w net.ipv6.conf.lo.disable_ipv6=1

# Upload the "PROXY" folder that you received in the "SSNPROXY.zip" onto your server.

#   If you are using the free version:
*      Replace line 5 in assets/config.json with your server IP
#   If you are using the paid version:
*      Replace line 3 in assets/dlc/config.json with your server IP

1. `chmod 777 *`

2. `./SSNPROXY`

3. CTRL + C

4. `screen -dmS SSNPROXY ./SSNPROXY`

5. `screen -r PROXY`

6. CTRL + a + d

Thats it, you are all setup. Enjoy!

Developed and distributed by: https://t.me/tcpsyn (Space)