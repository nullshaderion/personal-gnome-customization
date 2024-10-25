**Note you can install almost everything i said here via installing the desktop environment called hyprland!!**

# personal-gnome-customization
my gnome customization
REQUIREMENTS:
  - GNOME
  - ALACRITTY / KITTY
  - GNOME-EXTENSIONS MANAGER
gnome extensions list:
- ARCMENU
  * Go to layouts in menu and put modern and put kde
- BLUR MY SHELL
  * Go to apps or something in their settings and go to the bottom and select hteo ne u wana put blur to, then edit sigma and opacity, disable opaque focused window
- DASH TO PANEL
- WORKSPACE INDICATOR
- SPOTIFY CONTROLS + TRACK INFO
- TOPHAT

Also install gtk4 or whatever gtk theme!

now install oh my zsh && zsh via this command:

"sudo dnf install zsh" (assuming you're redhat)

also run this to set zsh as the main shell: chsh -s /usr/bin/zsh

this installs oh-my-zsh:
  * sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"  

zsh theme:
  powerlevel10k

oh-my-zsh or zsh plugin list:
  * firstly edit the ~/.zshrc file, on the plugins add, git, dnf, zsh-autosuggestions, zsh-syntax-highlighting
  * install pokemon color scripts, and at the zsh config file add the line: pokemon-colorscripts --no-title -s -r     --this will create a random pokemon everytime you boot up your terminal
  * set up icons using eza, make an alias in the zsh config file: alias ls = 'eza -a --icons' and add more!

now make an alias in zshrc, alias neofetch='neofetch | lolcat' to make it rgb when you run neofetch
also since i love cats i edited the neofetch config file in usr/bin to display a cat instead of the fedora logo (yes i use fedora)

this should be the results:


![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20182545.png)
![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20182551.png)

though it may not be the same you can achieve a similar appearance:

![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20185825.png)
![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20185947.png)
![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20190857.png)
![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20190923.png)
![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20193240.png)
![RESULT](https://raw.githubusercontent.com/nullshaderion/personal-gnome-customization/refs/heads/main/Screenshot%202024-10-19%20193501.png)

**Also forgot to mention that if you wish to achieve a similar look to my icons run the command in the terminal to install gnome tweaks**:
  - sudo dnf install gnome-tweaks
  - open tweaks and go to appearance and change the icons to tela
  - change the shell to "adwaita default"
  - change the legacy applications to "adwaita default"
  - change the cursor to breeze cursors
**if you dont see any of the options above run this:**
  - sudo dnf install gnome-themes-extra
