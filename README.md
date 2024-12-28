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

#### ```FPALERA PROFILE VIEWS 🧚```
![Visitor Count](https://profile-counter.glitch.me/FPALERA/count.svg)
