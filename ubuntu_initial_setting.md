0. ```$ sudo apt update && sudo apt upgrade```

1. Caps Lock to Ctrl
```bash
$ sudo apt install gnome-tweaks
$ gnome-tweaks
$ Keyboard & Mouse -> Additional Layout Option -> Ctrl position -> Caps Lock as Ctrl
```

2. hostname
```$ sudo hostnamectl set-hostname <hostname>```
then, reboot or logout

3. terminal
```bash
$ sudo add-apt-repository ppa:mattrose/terminator
$ sudo apt update
$ sudo apt install terminator
$ sudo update-alternatives --install /usr/bin/x-terminal-emulator x-terminal-emulator /usr/bin/terminator 1
$ sudo update-alternatives --config x-terminal-emulator
```
then, select ternimator

4. github
```bash
$ sudo apt install github
$ git config --global user.name "ou-ais"
$ git config --global user.email "yingchangjian1008@gmail.com"
$ ssh-keygen -t rsa -C "yingchangjian1008@gmail.com"
$ cd .ssh && cat id_rsa.pub
copy the key ssh -> login github page -> Setting -> SSH and GPG keys -> New SSH key -> paste
$ ssh -T git@github.com
```

5. ROS


6. miniconda
```bash
$ wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ bash ~/Miniconda3-latest-Linux-x86_64.sh
Enter
--yes--
--yes--
--Thank you for installing Miniconda3!--
$ conda config --set auto_activate_base false
```

7. nvidia driver & cuda

8. vscode

9. bashrc

10. language input (Pinyin)
sudo apt install ibus-libpinyin
sudo apt install ibus-clutter
Keyboard input method system -> ibus -> reboot
Setting -> Region & Language -> Input Sources -> add Chinese(Intelligent Pinyin)
