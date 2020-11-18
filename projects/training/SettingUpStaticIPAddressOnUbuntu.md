# Setting up a static IP address can be done through the GUI in Ubuntu 18.04.
{markdown: ./breadcrumb.md}

* Click your connection in top right menu bar.
* Click your connection and click wired/wi-fi settings
* Click the settings icon on the Wired/ Visible Networks section.
* In addresses (try in ipv4 tab if not visible, select manual):
    * for address, you will need to enter the static IP address of your choice (eg. 192.168.1.100).
    * set netmask to 255.255.255.0.
    * set gateway to the IP address of your network gateway (most likely 192.168.1.1).
* In DNS section, set this to your target devices current IP address (192.168.1.x), also can be found for the specific device by navigating to your gateway IP (192.168.0.1).
* Next to DNS section, set the Automatic switch to off.
* Click Apply.
* Disconnect internet (sudo dhclient -r && sudo dhclient) or just disconnect, and connect again and navigate to gateway settings, your device should now have adopted the static IP (192.168.0.3) you set.

### Links
* [How to Configure Static IP Address on Ubuntu 18.04 (Desktop)](https://tecadmin.net/change-ip-address-on-ubuntu-18-04-desktop/) 


     
    
    
    


   





  

