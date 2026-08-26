# Anonymous-os-in-android-
✨ Features 🖥️ Custom Anonymous-style terminal interface 💀 Personalized ASCII/Neofetch system information 🟢 Hacker-style terminal theme ⚙️ Useful Termux/Linux command-line utilities 📱 Designed for Android + Termux 🚀 Lightweight and easy to customize 🔧 Modular scripts for adding your own tools and features

#step 1.download 🗃️ from release 

# step 2.run command one by one


$ termux-setup-storage


$ pkg update


$ pkg install unzip


$ unzip AnonymousOS_Termux_CLI.zip


$ cd AnonymousOS_Termux_CLI


$cp -r ~/storage/downloads/AnonymousOS_Termux_CLI ~/


$ cd


$ cd ~/AnonymousOS_Termux_CLI


$ chmod +x install.sh


$ bash install.sh


$ source ~/.bashrc


$ osinfo


$ cd ~/storage/downloads && rm -rf AnonymousFetch && unzip -q AnonymousFetch_Termux.zip -d AnonymousFetch && cp AnonymousFetch/anonymousfetch "$HOME/anonymousfetch" && chmod +x "$HOME/anonymousfetch" && mkdir -p "$PREFIX/bin" && cp "$HOME/anonymousfetch" "$PREFIX/bin/anonymousfetch" && grep -qxF 'command -v anonymousfetch >/dev/null && anonymousfetch' "$HOME/.bashrc" || echo 'command -v anonymousfetch >/dev/null && anonymousfetch' >> "$HOME/.bashrc" && anonymousfetch
