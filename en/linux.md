---
title: "How to connect to Kawata (Linux)"
old_id: 14
---
This guide is only for connecting osu! to Kawata, and not setting the game itself up. You can follow [this guide](https://gist.github.com/Francesco149/a2f796683a4e5195458f4bb171d88eb0) to set the client up.

### Modifying the hosts file
For this, you will need to modify your *hosts* file. To do so, run `nano /etc/hosts` as root/with sudo.

When you've got it open, paste the following at the bottom:

```
88.198.32.217 osu.ppy.sh
88.198.32.217 c.ppy.sh
88.198.32.217 c1.ppy.sh
88.198.32.217 c2.ppy.sh
88.198.32.217 c3.ppy.sh
88.198.32.217 c4.ppy.sh
88.198.32.217 c5.ppy.sh
88.198.32.217 ce.ppy.sh
88.198.32.217 a.ppy.sh
88.198.32.217 i.ppy.sh
```
**CTRL+X** and then **Enter** to save the file.

### Installing the certificate
Download the certificate by clicking [*here*](https://raw.githubusercontent.com/osukawata/Kawata-Switcher/master/GatariSwitcher/Resources/cert.crt)

Open the Internet Explorer configuration by running `wine control`.

Double click the *Internet Settings* icon, navigate to the *Content* tab, then click the *Certificates...* button.

Click on *Import*, then *Next*.

Click *Browse...* then select the Kawata certificate.

Click *Next*.

Select *Place all certificates in the following store*, and click *Browse*.

Select **Trusted Root Certification Authorities**, and click *Ok*.

Click *Next*, *Finish*.

You should get a message saying **The import was successful**.


After that is done, you can start the client up, and log in with your Kawata credentials.