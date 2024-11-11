# termux-bashrc

Custom termux bash.bashrc file with preset aliases and terminal splash screen. 

## Installation:

1. Clone the repository.
```
cd $HOME && git clone https://github.com/knightfall-cs/termux-bashrc.git
```
2. Backup your current .bashrc file.
```
cd /data/data/com.termux/files/usr/etc && cp -v bash.bashrc $HOME/termux-bashrc/backup/ && cd -
```
3. Copy the bash.bashrc file to your .../usr/etc directory.
```
cd termux-bashrc && cp bash.bashrc /data/data/com.termux/files/usr/etc && exit
```
 4. Done. Now restart Termux.
 
## Usage:

- Type `edit-bashrc` to edit and view the file.
- You can change username and default editor by changing variables in # Global.
- You can also customize prompt color scheme and symbol by changing preferred variables in # Prompt.

---
Author: KNIGHTFALL
