🐧 Install Visual-Studi-Code in Linux.


 ```Debian and Ubuntu based distribution```

- Easiest way to download VsCode for Debian/Ubuntu based distributions is to download and install the [.deb package ](https://go.microsoft.com/fwlink/?LinkID=760868)
- After Downloading the .deb package, Open the Terminal, Cd to the .deb package.
- Use this Command to Install sudo apt install ./<file>.deb
 
```
Fedora, CentOS, and RHEL based distributions
```
- Open the Terminal & Run the following commands.

```
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
```
 - Update dnf & Install.
 
      ```
    ↳ dnf check-update
      ```
      ```
    ↳ sudo dnf install code
      ```
 
 ```
 Arch Linux
 ```
 -  Open the Terminal & Type the following commands.
 -  sudo pacman -Sy
 -  sudo pacman -S git
 -  cd ~/Downloads.
 -  git clone https://AUR.archlinux.org/visual-studio-code-bin.git
 -  cd visual-studio-code-bin/
 -  makepkg -s
 -  sudo pacman -U visual-studio-code-bin-1.71.2-1-x86_64.pkg.tar.zst 


