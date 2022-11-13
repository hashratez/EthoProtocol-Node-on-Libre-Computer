# EthoProtocol-Node-on-Libre-Computer
Run your own EthoProtocol Gateway Node for $70 -- 1/3 the price of a Pi!

Libre Roc 4 Gig $59

https://www.amazon.com/Libre-Computer-ROC-RK3328-CC-Renegade-Ethernet/dp/B078RT6H8X?linkCode=sl1&tag=loverpi05-20&linkId=18e88dea68d9624c8cf77b55a9ec685a&language=en_US&ref_=as_li_ss_tl&th=1

Download Ubuntu Image

Index: https://distro.libre.computer/ci/ubuntu/22.04/

Latest Server Edition File (12NOV22): https://distro.libre.computer/ci/ubuntu/22.04/ubuntu-22.04.1-preinstalled-server-arm64%2Broc-rk3328-cc.img.xz

Extract

Flash Image onto microsd card (they recommend not using Belenda but seems to work fine)

Default login: ubuntu

Default password: ubuntu

You will be immediately prompted to change the password, then you will login again as user "ubuntu" with your new password.

Update & Upgrade

Adduser "ether1node"
Adduser "ether1node" to sudo

Reboot and login as user "ether1node"

```
wget https://raw.githubusercontent.com/Ether1Project/EthoProtocol-Raspberry-Pi-Node/main/preprocess.sh
chmod u+x preprocess.sh
sudo su -c ./preprocess.sh
```

Reboot, login as user ether1node again

Login to https://nodes.ethoprotocol.com

Select your node type and provide wallet address, take the auto generated script and run on the Roc.

DONE.
