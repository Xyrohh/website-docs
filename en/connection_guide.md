---
title: "How to play on Kawata"
old_id: 1
---

## Video tutorial
We now have a video tutorial to get you up and running in no time!
<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/imdQcbwOoi0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>

# Registering on Kawata
To create your Kawata account, follow [this link](/register), and follow the instructions to create your account.
<br>
Make sure you read the [rules](/doc/rules) before proceeding!

# Connecting to Kawata

## New method (-devserver flag)
osu! has recently added *official-ish* support for private servers. That means you can now easily connect to Kawata, without tampering with your system files. This is the recommended method. Please note that some unofficial osu! clients may not be compatible with this new method yet.

### Launching osu! on Kawata

- Open your osu! installation folder.
- Click the address bar, and type `osu!.exe -devserver kawata.pw`.
- Open osu! and login with your Kawata account.

### Creating a shortcut to connect quickly

- Open your osu! installation folder.
- Create a shotcut to osu!.exe wherever you want, or copy your existing shortcut.
- Right-click your newly created shortcut, and click **Properties**.
- In the **Target** field of the **Properties** window, add `-devserver kawata.pw` to the existing text.
- Open your newly created shortcut and login with your Kawata account.

## Old method (server switcher)
This is the traditional method for connecting to private servers. This method requires administrator access, as it implies tampering with the osu! certificate, and the hosts file. This method is considered legacy and should only be used in cases where the new method cannot be used.

### Certificate installation
If you want to play on Kawata, you must install our HTTPS certificate.  
Do this only the first time you connect to Kawata.  

- Open the switcher.
- Click on **"Install certificate"**.
- Click **"Yes"**.

*If you can't install the certificate properly, follow [these instructions](/doc/install_certificate_manually) to install it manually.*

### How to connect to Kawata
- Run the switcher **as administrator**
- Click "Connect to Kawata".
- Make sure that the switcher says **"You're connected to Kawata!"** (it should look like [this](https://i.imgur.com/0LotBDY.png)), if not, click **"Connect to Kawata"** to switch server.
- Open osu! and login with your Kawata account.

### How to play on official osu! again
- Make sure osu! is **closed**  
- Open the switcher and make sure it says **"You are playing on Bancho"** (it should look like [this](https://i.imgur.com/JwrBy8S.png)), if not, click **"Disconnect from Kawata"** to switch server.
- Open osu! and login with your osu! account.
_NOTE:_ If you want to connect to osu.ppy.sh and you still see Kawata's website even if the switcher is off, empty your browser cache.

### How to update osu!/switch release branch
- Make sure osu! is **closed**.
- Open the switcher and make sure it says **"You are playing on Bancho"** (it should look like [this](https://i.imgur.com/JwrBy8S.png) ).
- Open osu! and update the game.

## Having troubles?

Check out our [FAQ](/doc/faq)
