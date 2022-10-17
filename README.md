# anonsurf-autochange
Simple Script To Automatically Change Your Anonsurf Identity Every 8 Seconds


Usage
===============
cd anonsurf-autochange
sudo su
anonsurf start
bash autochange.sh


How To Install AnonSurf
=================================

Parrot
-------------
Parrot automatically comes with AnonSurf built in. All you need to do is start AnonSurf and then run the script as root


Kali-Linux
---------------
 You need to install anonsurf for kali at the following github repo:
 https://github.com/Und3rf10w/kali-anonsurf
 
 Type: cd kali-anonsurf
 Type: bash installer.sh
 
 How To Use AnonSurf
 --------------------------------
 Usage:
 anonsurf {start|stop|restart|change|status}

 start - Start system-wide anonymous
          tunneling under TOR proxy through iptables
 stop - Reset original iptables settings
          and return to clear navigation
 restart - Combines "stop" and "start" options
 change - Changes identity restarting TOR 
 status - Check if AnonSurf is working properly
----[ I2P related features ]----
 starti2p - Start i2p services
 stopi2p - Stop i2p services
