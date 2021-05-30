## How to install

- Install [Choose Gui](https://github.com/chipsenkbeil/choose) with the command `brew install choose-gui`

### Intel macs

- Install pip packages: `pip3 install osascript` and `pip3 install tldextract`

### M1 macs

***There seems to be issues if you have both intel and m1 version of homebrew installed***

---

The problem is the qutebrowser uses the `/usr/local/bin/python3` version of python and you can also have python3 install
on `/opt/homebrew/bin`. So I just installed the  `pip3 install osascript` and `pip3 install tldextract` in both `/opt/homebrew/bin/pip3` and
on the `/usr/bin/pip3`. You can also just try the `/usr/bin/pip3` version


### Installing for qutebrowser

- Copy bitwarden script to `$HOME/.qutebrowser/userscripts`

Then when you are in a page run `spawn --userscript bitwarden` 

And that's all folks 

![image](https://media1.tenor.com/images/03e054d9928b5137884289352d9ae9cb/tenor.gif)
