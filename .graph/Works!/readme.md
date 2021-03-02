# How to connect RDP from ubuntu 20.10 [complete]
https://blog.eldernode.com/how-to-connect-rdp-from-ubuntu-20-10/

code:
nano /etc/xrdp/startwm.sh
The content of the file should look like this: (Note the last line)

```#!/bin/sh  if [ -r /etc/default/locale ]; then  . /etc/default/locale  export LANG LANGUAGE  fi  startxfce4
```
