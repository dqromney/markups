# My Guides
{markdown: ./breadcrumb.md}

### Links

- [How to put a Linux ISO onto a USB stick and make it bootable on a Mac](https://linuxnewbieguide.org/how-to-put-a-linux-iso-onto-a-usb-stick-and-make-it-bootable-on-a-mac/)
- [Tutorial: Create a USB stick on Ubuntu](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-ubuntu#0)
- [Docker: Introduction to Compose-file](https://severalnines.com/blog/mysql-docker-composing-stack)
- [ZyXEL C1100Z USB Port Question](https://www.reddit.com/r/HomeNetworking/comments/4n1llk/zyxel_c1100z_usb_port_question/)
    * Although this type of USB port is shown in the example above the port is currently non-functioning. It may be enabled in a future firmware release.
- [Java Version Manager inspired by nvm (Node.js). Written in Go.](https://github.com/shyiko/jabba)
  - The goal is to provide unified pain-free experience of installing (and switching between different versions of) JDK regardless of the OS (macOS, Linux x86/x86_64/ARMv7+, Windows x86_64).
- [How to enable SMB1 on Windows 10 (Drobo FS)](https://www.tachytelic.net/2019/09/windows-10-enable-smb1/#:~:text=Enable%20SMB1%20on%20Windows%2010%201%20Press%20Windows,access%20shares%20using%20the%20SMB%201%20Protocol%20again.)
  - Enable SMB1 on Windows 10 with PowerShell
    - `Enable-WindowsOptionalFeature -Online -FeatureName "SMB1Protocol-Client" -All`
    - [SBMV1 is not installed by default in windows 10](https://support.microsoft.com/en-gb/help/4034314/smbv1-is-not-installed-by-default-in-windows)
  - Enable SBM1 on Windows 10
    1. Press Windows Key + R to bring up the run dialog and type: `optionalFeatures`
    0. Expand “SMB 1.0/CIFS File Sharing Support” and then check the box next to “SMB 1.0/CIFS Client“
    0. Click Okay
    0. The installation will now proceed and you should be able to access shares using the SMB 1 Protocol again.
  
Things to install on Ubuntu
* vim - sudo apt install vim
* ssh - sudo apt install ssh
* java - sudo apt install java.default ?
* java - sudo apt install nodejs

