# Graphite Vortex Modified Server

Basic knowledge of Linux
A VPS (e.g. Amazon Web Services, Microsoft Azure)
Any Linux distribution.
It is recommended to use Ubuntu.
Python 3.10.12

1 GB free Memory (Recommended 2 GB)

Requirements

| Software/ Language | Version |
|----------|---------|
| Python | 3.10.12 |
| Ubuntu | 22.04 |


Download files on terminal -
```
git clone https://github.com/hypervortex/VH-Bombsquad-Modded-Server-Files &&
cd VH-Bombsquad-Modded-Server-Files &&
sudo chown -R ubuntu:ubuntu /home/ubuntu/VH-Bombsquad-Modded-Server-Files
```

## 𝙄𝙣𝙨𝙩𝙖𝙡𝙡𝙖𝙩𝙞𝙤𝙣 𝙋𝙧𝙤𝙘𝙚𝙨𝙨 - 𝘼𝙪𝙩𝙤𝙢𝙖𝙩𝙞𝙘 𝙄𝙣𝙨𝙩𝙖𝙡𝙡𝙖𝙩𝙞𝙤𝙣:

Run the perms - 
```
chmod 777 bs_requirements.sh
```
Run the file
```
sudo ./bs_requirements.sh
```

Required packages downloaded, for manual installation see below
Now you can edit rest files

## 𝙈𝙖𝙣𝙪𝙖𝙡 𝙄𝙣𝙨𝙩𝙖𝙡𝙡𝙖𝙩𝙞𝙤𝙣:
- Open terminal, run the followng commands:

  - `sudo apt update; sudo apt install software-properties-common -y`
  - `sudo add-apt-repository ppa:deadsnakes/ppa`
  - `sudo apt install python3-pip python3.10-dev python3.10-venv`
  - install the pymongo and psutil
  - `sudo apt install python3-pip -y`
  - `sudo pip3 install pymongo --target=/usr/lib/python3.10`
  - `sudo pip3 install psutil --target=/usr/lib/python3.10`
  - `sudo pip3 install ping3 --target=/usr/lib/python3.10`


## 𝘾𝙧𝙚𝙖𝙩𝙚 𝙖 𝙏𝙈𝙐𝙓 𝙨𝙚𝙨𝙨𝙞𝙤𝙣:
- How to run server:

  - `tmux new -s 43210`
  - `cd (Your_folder_name)`
  - edit config.yaml ---> change server name, team names, team colors, etc
  - `chmod 777 bombsquad_server`
  - `chmod 777 dist/bombsquad_headless`
  - start the server - `sudo ./bombsquad_server`
  - More Configurations  --->
  - Open dist/ba_root/mods/setting.json in your prefered editor and change values according to you.
  - Knowledge of BCS files and basic editing senses is expected.

# 𝙁𝙚𝙖𝙩𝙪𝙧𝙚𝙨
- [X] Includes latest BCS-Server features and special features by me - shivraj-bhatt

### 𝙎𝙥𝙚𝙘𝙞𝙖𝙡 𝙑H 𝘾𝙈𝘿𝙎 𝙗𝙮 𝙈𝙚:

Special Commands
``
zoommessage (zm), fall, speedon, hug, icy, spaz, top, zombieall, boxall, texall, kickall, ooh, spazall, acl (admin cmd list), vcl ( vip cmd list ), tint, ac, comp ( to file complaint agaist player, but u need to setup dc bot to use this cmd), playsound 
``
- [X] Time and member count in textonmap
  - `To enable the time, open the terminal, and change the TIMEZONE to desired`
  - `Example - sudo timedatectl set-timezone <your_time_zone>`
  - `Find your timezone in terminal - timedatectl list-timezones`
- [X] Modified season reset count down which is fully visible

