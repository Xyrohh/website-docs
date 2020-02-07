---
title: "Installing the certificate manually"
old_id: 12
---
If you're having troubles connecting to Kawata using stable (latest)/beta/cuttingedge or the switcher doesn't install the certificate properly, you can install the certificate manually.

### Instructions
- First, download the certificate [by clicking here](https://raw.githubusercontent.com/kawatapw/hanayo/732a62e13b56a0819e47b3f0d24aa5f9bc8bbcfc/static/cert.crt)
- Then, open **certificate.crt**
- Click **Install certificate...**
- Click **Next**
- Select **Place all certificates in the following store** (second option), then click **Browse...**
- A new window will pop up, select **Trusted root certification authorities** and click **Ok**
- Click **Next**
- Click **Finish**

### How to test the certificate
To ensure the certificate has been installed successfully, make sure the switcher is **On** and open [this page](https://c.ppy.sh).  

- If you see **[osu!bancho stuff](http://y.zxq.co/ubfzty.png)**, your switcher is off. **Turn it on and try again.**  
- If you see **[some kawata stuff](http://y.zxq.co/zphobw.png)**, you're successfully connected to Kawata under https, **good job!**  
- If you get **[some certificate or security error](http://y.zxq.co/reaueu.png)**, the certificate has not been installed successfully. **Follow the instructions below.**  

### If everything else fails...
...you can try to remove all existing Kawata/Ripple/Akatsuki/Enjuu/Whatever certificates and install the certificate again. Follow these steps:

- Press **Win+R**  
- Type `mmc certmgr.msc` in the run box and press **enter** to open the Certificate Manager  
- Select **Trusted root certification authorities** on the left  
- Select **Certificates** on the right  
- You should see a **[Ripple](http://y.zxq.co/bbyxev.png)** entry and one or two **\*.ppy.sh** entries in the list. Select them, **right click** and click on **Delete**  
- Select all the positive options  
- Open the switcher, click on **Install certificate**, then **Yes**  
- Try to connect to [Kawata's bancho server under https](https://c.ppy.sh/) and it _should_ work  
