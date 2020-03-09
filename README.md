# How-to-use-app-1.1.1.1-on-PC

## Step 1: Install TunSafe

    - Download *TunSafe* at (https://tunsafe.com/download)
    - After installed, choose *File -> Generate Key Pair...*
    - Click on **Randomize** to get **Private Key** and **Public Key**

## Step 2: Run Python script to get configuaration Warp+

    - Go to (https://repl.it/languages/python3)
    - Copy the script from (https://raw.githubusercontent.com/HoangVNH/How-to-use-1.1.1.1-on-PC-/master/script.py)
    and paste it to main.py
        - Run it
        - Press y and hit enter
        - Copy the **Private Key** from TunSafe and paste it and hit enter
        - Copy the **Public Key** from TunSafe and paste it and hit enter
        - If it works, then you will have 2 files: *wgcf-identity.json* and *wgcf-profile.conf*
        - Click into *Three dots* button on the left side, click on *Download as zip* and unzip it.
        
## Step 3: Setup to use Warp+ 1.1.1.1 with TunSafe
    - Open *TunSafe*
    - File -> Browse in Explorer
    - Copy wgcf-profile.conf into Config folder 
> Default is *C:\Program Files\TunSafe\Config*
    - Open *TunSafe* and choose *wgcf-profile* in the dropdown menu to connect to Warp+
