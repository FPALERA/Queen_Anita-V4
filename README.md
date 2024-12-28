 ## QUEEN_ANITA-V2 Deployment Methods

### 1. COPY THIS REPO

```
git clone https://github.com/FPALERA/Queen_Anita-V4 FP_BOT
```

### 2. GET SESSION ID HERE

### SERVER 1 
 
<a href="https://anita-v4-pairing.onrender.com/pair"><img src="https://img.shields.io/badge/SESSION_ID-blue" alt="Click Here to Get Pair-Code" width="110"></a>   

#### Manual Installation

1. **Install Git, ffmpeg, and curl:**
    ```sh
    sudo apt -y update && sudo apt -y upgrade
    sudo apt -y install git ffmpeg curl
    ```

2. **Install Node.js:**
    ```sh
    curl -fsSL https://deb.nodesource.com/setup_20.x -o nodesource_setup.sh
    sudo -E bash nodesource_setup.sh
    sudo apt-get install -y nodejs
    ```

3. **Install Yarn:**
    ```sh
    sudo npm install -g yarn
    ```
    
4. **Install pm2:**
    ```sh
    sudo yarn global add pm2
    ```
    
5. **Install Packages:**
    ```sh
    cd FP_BOT
    npm install
    yarn install
    ```

**Edit `/session/creds.json `Using Nano (if needed):**
    - To save, press `Ctrl + O`, then press `Enter`, and to exit, press `Ctrl + X`.

8. **Start and Stop the Bot:**
    - To start the bot:
      ```sh
      pm2 start . --name FP_BOT
      ```
    - To define autostart:
      ```sh
      pm2 save
      pm2 startup
      ```
      
#### Obtenir un serveur ici
<a href="https://www.digitalocean.com/?refcode=1ddbfbb00962&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge"><img src="https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg" alt="DigitalOcean Referral Badge" /></a>

#### CONTACTS
<a href="https://wa.me/22658179319"><img src="https://static.whatsapp.net/rsrc.php/yZ/r/JvsnINJ2CZv.svg" alt="Whatsapp" /></a>
<a href="https://t.me/FPALERA"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADgAAAA4CAMAAACfWMssAAAAclBMVEX///8oqOknpuYkod4jn9slo+EjoNwkot8mpeQpqespquwop+gnp+cmpOMlouAnp+gAnN8ApOvt9vz4+/43qeUJm9rh8Pui0/VOs+2z2fMOoeNvvOvL5faJxu0AltiTzPN8w/HW6vldtei83fOYyutFqd84rg+kAAACcElEQVRIiZWX24KqMAxFOx50hDlCqlQh5abC///iBERpSinMfoI2q9mkF6sQLl3zWmdpFKWZrvOrM8ShopGkMIxIYRjSc1NswG6hHBBTBN/WMDnHRtaH3iPppAbJcNFwuZDtk7R0cxkVxC+ZXebYOVrDBp1n3CbMQUbh1yaFIXebJVszhhmv57Z8vcza3v/AETnN51fyFzBJ3twNkz8J2xGUyc+akh8jJpGXMeEahTLJ0CDHlLvkv08JYnmnvY1GG/ZcIX0Yyuz5+qCd2doXtvE4pWTvg+NihqGmFtwtCdPcWMxgdkHvfYECfTcXVyHNXnkVTzzOdUKsrW2QszjMRe3ICIbHZnzkcVgKbYMIj8ljgen4pHmQFtnJ8lhOHi8NdO/nlMdlIjWdUx2NfVqccNp8dimEMQo82AHYAD6M2bDB00dHXn5y/TBe8cRF3kchOzUbOEFjvN8s8CiyeD9qWl7ivsc98IFwbyruaDo+bwhpWVBxziXEe6hNTnQxA2k6auYBAdMUqAk5Jyyn9F0590Au4pcVpjPwIFpyV6tppFMOFtbwQOWA+Nuh+MFO7BvyXhjqFTuFTwPUVme/kQtwgzHoKWlqdQ2DotNrbyh+J70A71FDa6sWwO9P0jsPUa1zOIYO55k9Nozf0MK/ZUFzFlfFmtT7J0B4OAoj8ZZ4mt7Kix74a2Xs2lIdNkuxXdMF3pyGAr6KL4dgW74gsK46Z7WJDNT8orMlZxDMOHLbqWBFqnNcyfraVn6uWrgE0nwGnqQq8N2T22oBVVXrwfovbWmFzTHVur+OG9ZVNcE0TqWf69RL17zUHRX/0Oly4e/DL99pVpSHprz9AAAAAElFTkSuQmCC" alt="Telegram" /></a>

#### ```FPALERA PROFILE VIEWS 🧚```
![Visitor Count](https://profile-counter.glitch.me/FPALERA/count.svg)
