Customisation & Configuration
-----------------------------

First Steps
^^^^^^^^^^^

After the restart log in as ``root``

.. code-block:: console

   $ apt-get update              # update package database
   $ apt-get upgrade             # upgrade to the latest version
   $ apt-get install sudo zsh


.. code-block:: console

   $ usermod -aG sudo <username> # grant sudo priviledges to <username>
   $ chsh <username> -s /bin/zsh # change login shell for <username>
   $ chsh -s /bin/zsh            # change login shell for root
   $ logout                      # C-d works too

log in as ``<username>``


Basic user interface
^^^^^^^^^^^^^^^^^^^^

* oh-my-zsh

.. code-block:: console

   $ # Temporary. I want to use Antigen (http://antigen.sharats.me) later
   $ sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
   $ git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
   $ ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
   $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting


* zsh: spaceship prompt

.. code-block:: console

   $ sudo apt-get install vim-gtk tmux sshfs git ranger pulseaudio stow

.. code-block:: console

   $ git clone  https://github.com/hugligit/dotfiles.git
   $ git pull origin master 
   $ git push -u origin master

oh-my-zsh
"""""""""
TODO: Configuration

.. code-block:: console

   $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
   ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting


zsh: spaceship prompt
"""""""""""""""""""""
TODO: Configuration

vim-gtk
"""""""
TODO: Configuration

tmux
""""
TODO: Configuration

sshfs
"""""
TODO: Configuration

git
"""
TODO: Configuration

ranger
""""""
TODO: Configuration

pulseaudio
""""""""""
TODO: Configuration


X Server
^^^^^^^^

.. code-block:: console

   $ sudo apt-get install feh i3 rofi terminator unclutter xbindkeys xchainkeys xorg xscreensaver

* fonts
* background image
* xinitrc

feh
"""
TODO: Configuration

i3
""
TODO: Configuration

rofi
""""
TODO: Configuration

terminator
""""""""""
TODO: Configuration

unclutter
"""""""""
TODO: Configuration

xbindkeys
"""""""""
TODO: Configuration

xchainkeys
""""""""""
TODO: Configuration

xorg
""""
TODO: Configuration

xscreensaver
""""""""""""
TODO: Configuration

pamix
"""""


Programs
^^^^^^^^

.. code-block:: console
   
   $ sudo apt-get install alsautil anki chrome cmus \
   firefox libreoffice mplayer python zathura



alsautil
""""""""
TODO: Configuration

anki
""""
TODO: Configuration

chrome
""""""
TODO: Configuration

cmus
""""
TODO: Configuration
include ``set output-plugin=pulse``

firefox
"""""""
TODO: Configuration

libreoffice
"""""""""""
TODO: Configuration

mplayer
"""""""
TODO: Configuration

python
""""""
TODO: Configuration

zathura
"""""""
TODO: Configuration


Games
^^^^^

leela
"""""""
TODO: Configuration

wesnoth
"""""""""
TODO: Configuration
