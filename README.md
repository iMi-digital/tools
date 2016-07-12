# OpenWeb

## Descripion
After the handing over of the URL to the script.
The script automatically builds up a ssh connection to the accompanying web servers.
Here one has the choice whether one ssh or sshrc would like to use and also the possibility to customise the user.
As soon as all important data is given the connection to the server is erstablished.
Here the real function of the script appears, because the script automatically searches for the given domain and opens the right Documentroot and passes the control of the shell to the user.

OpenWeb works only with apache2

### Usage
```
ow www.google.com
```
![Demo](https://raw.githubusercontent.com/iMi-digital/tools/master/doc/ow-demo.gif)
