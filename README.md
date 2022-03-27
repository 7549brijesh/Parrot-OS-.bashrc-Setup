# Parrot-OS-.bashrc-Setup

This is the .bashrc file, or at least as similar one that Parrot OS has.

# Usage

Replace your .bashrc file with this one. For example:
This will remove your current .bashrc file and copy your new one from your downloads folder into your home folder.
$ rm /home/$USER/.bashrc && cp /home/$USER/downloads/.bashrc /home/$USER/
Then run
$ source .bashrc
to "restart" your session, it'll load the new .bashrc file in.
