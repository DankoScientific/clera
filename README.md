# clera
A new type of clear

I accidentally type clera instead of clear all the time. This script clears the screen and then runs ls -Ssh which does the following:

* S sorts by filesize, largest first
* s prints size of each file in blocks
* h makes everything human readable

To install:

```
sudo chmod +x clera

sudo mv clera /usr/local/bin/
```
