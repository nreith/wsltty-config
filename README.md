# wsltty_conf
My setup for wsltty terminal (mintty) for Windows Subsystem for Linux

## Credit to:

1. Nick Janetakis for all things Linux on Windows, including his WSLTTY config setup:
https://nickjanetakis.com/blog/configuring-wsltty-which-is-my-favorite-windows-wsl-terminal

2. These repos for themes:

- https://github.com/iamthad/base16-mintty
- https://github.com/mskyaxl/wsl-terminal

## Usage

Assuming:

- you already have Windows Subsystem for Linux
- WSLTTY installed
- git installed in WSL
- and your Windows and WSL usernames are the same:

run the following in a Bash terminal window:

```bash
cd /tmp
git clone https://github.com/nreith/wsltty_conf.git
cp wsltty_conf/themes/* /mnt/c/Users/$USER/AppData/Local/wsltty/themes/
cp wsltty_conf/.minttyrc /mnt/c/Users/$USER/AppData/Local/wsltty/home/$USER/
```

Then start a new WSLTTY session.
