
<br>
  
  ```html
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
  ```
  
♦️ For Ubuntu 18.04 Only For First Time Installation <br>
  
  ```html
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
```

♦️ Installation Link (Recommended Debian 10) <br>

  ```html
apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/annelyah23/cactus/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
```
