<div align="center">
   <img src="https://github.com/trueToastedCode/ParallelsLab/assets/44642574/e05554fe-b335-42dc-87d6-7a3780916706" width=128 height=128>
   <h1>Parallels Desktop Crack</h1>
   <div>19.1.1-54734</div>
</div><br><br>

✅ ARM64<br>
✅ x86_64<br>
✅ Network<br>
✅ USB<br>
✅ System Integrity Protection (SIP)<br>
✅ No additional launcher<br>
❌ Open Source<br><br>

## Disclaimer
The use of software cracks for illegal purposes is strictly prohibited and we encourage the legal purchase and use of the software. By using this software or reading this disclaimer, you acknowledge that you understand the importance of legal software usage and that you will not use software cracks or engage in illegal activities related to software.

## Usage
1. [Install Parallels Desktop (19.2.0-54827)](https://download.parallels.com/desktop/v19/19.2.0-54827/ParallelsDesktop-19.2.0-54827.dmg)<br>
2. Sign out your account
3. Clone the respository:<br>
`git clone -b macked --depth 1 https://github.com/trueToastedCode/ParallelsLab.git ParallelsLabMacked`
4. Install Parallels Desktop Activation Tool using the dmg (Try 4.4.0, consider 4.4.1 if you experience issues)
5. Remove quarantine:<br>
`sudo xattr -d com.apple.quarantine /Applications/Parallels\ Desktop\ Activation\ Tool.app`
6. Using Finder, navigate to the application folder, click on the application while holding control and choose open. This allows the execution from an unverified developer

## Sidenotes
### Info
This crack comes from [macked.app](https://macked.app/parallels-desktop.html). Up fom this verison, they solved the entitlements problem, which i haven't solved (yet). If you don't trust them, my Open Source crack is still avaialble in another branch.

### Issues
[Report issues here](https://github.com/trueToastedCode/ParallelsLab/issues)

## Hosts
You also want to block Parallels Servers.
```
127.0.0.1 download.parallels.com
127.0.0.1 update.parallels.com
127.0.0.1 desktop.parallels.com
127.0.0.1 download.parallels.com.cdn.cloudflare.net
127.0.0.1 update.parallels.com.cdn.cloudflare.net
127.0.0.1 desktop.parallels.com.cdn.cloudflare.net
127.0.0.1 www.parallels.cn
127.0.0.1 www.parallels.com
127.0.0.1 www.parallels.de
127.0.0.1 www.parallels.es
127.0.0.1 www.parallels.fr
127.0.0.1 www.parallels.nl
127.0.0.1 www.parallels.pt
127.0.0.1 www.parallels.ru
127.0.0.1 www.parallelskorea.com
127.0.0.1 reportus.parallels.com
127.0.0.1 parallels.cn
127.0.0.1 parallels.com
127.0.0.1 parallels.de
127.0.0.1 parallels.es
127.0.0.1 parallels.fr
127.0.0.1 parallels.nl
127.0.0.1 parallels.pt
127.0.0.1 parallels.ru
127.0.0.1 parallelskorea.com
127.0.0.1 pax-manager.myparallels.com
127.0.0.1 myparallels.com
127.0.0.1 my.parallels.com
```
Parallels Desktop will uncomment these, therefore one needs to lock the hosts file:<br>
`sudo chflags uchg /etc/hosts && sudo chflags schg /etc/hosts`<br>
Unlock:<br>
`sudo chflags nouchg /etc/hosts && sudo chflags noschg /etc/hosts`
### OS download
You will not be able to download operating systems in the Control Center anymore. Comment these out to get this functionality:
```
# 127.0.0.1 download.parallels.com
# 127.0.0.1 desktop.parallels.com
# 127.0.0.1 download.parallels.com.cdn.cloudflare.net
# 127.0.0.1 desktop.parallels.com.cdn.cloudflare.net
```
