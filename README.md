# Install software
```bash
git clone https://github.com/sonnyyu/docker-wireshark/
cd docker-wireshark
```
# Getting started
```bash
docker-compose up -d
```
# Quit 
```bash
docker-compose down 
```
# Quit and remove volume 
```bash
docker-compose down -v
```

# Open wireshark web interface
http://192.168.1.204:3000

# If you want to allow to share your session, use
   
http://192.168.1.204:3000/?sharing=true
