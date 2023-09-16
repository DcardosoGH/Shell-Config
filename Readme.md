# Shell Configs

My settings for shell config and tmux based on https://github.com/siddicky/DotFiles

Check that repo for further instructions on Dependencies.

# Installation

Make sure to have the following installed (you can find the links at the Siddicky repo):

- Tmux Plugin Manager

- Oh My Zsh

- Zsh Autosuggestions

- True Color


<br>
After installing, copy all the files to the home directory of your user.

My advice for checking if everything is correc is simply running ``source ~/.zshrc`` and look at any errors loading.

### Common errors:

- Place the vpn.sh inside ``~/opt/``
- Plugin x is not installed
    - Download the plugin and put it inside `` ~/.oh-my-zsh/plugins/<plugin-folder>/<plugin-name>``
- Tmux pluggins not properly installed:
    - To install Tmux plugins, first install TPM: https://github.com/tmux-plugins/tpm
    - After it is installed, run:  `` Press prefix + I (capital i, as in Install) to fetch the plugin. `` 
    - The plugins are now installed

- Font is Iosevka Fixed XBd Ex 14pt
- Place the oh-my-zsh theme inside `` ~/.oh-my-zsh/themes/<theme-name>``

## Screenshot
<br>

![Alt text](/Screenshot.png?raw=true "Screenshot")
