## HLDS Server for Counter-Strike 1.6
HLDS Build ```7882``` [24-06-2018]  
Metamod ```v1.21.1-am``` & DProto ```0.9.582```

<img src="https://files.catbox.moe/f66s3s.png">

---

## Downloading
```
wget https://github.com/codeowais/hlds-cstrike/releases/download/7882/hlds-backup-2025-12-06.tar.gz
```

---

## Installation (Debian-based)

### Automated install
```
wget https://github.com/codeowais/hlds-cstrike/releases/download/7882/install-hlds.sh
sudo chmod +x install-hlds.sh
./install-hlds.sh
```
All server binaries will be located in the ```hlds\``` directory

---

### Manual install

Add the 32-bit architecture (only for 64-bit OSes)
```
sudo dpkg --add-architecutre i386
```

Install the HLDS dependencies
```
sudo apt update & sudo apt install tar libc6:i386 libc6 lib32gcc-s1 lib32stdc++6 -y
```

Finally, extract the package
```
tar -xvzf hlds-backup-2025-12-06.tar.gz
```

All server binaries will be located in the ```hlds\``` directory
