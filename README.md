# OpenWeb

Open Web Root of a Domain

## Description

After the handing over the domain to the script, the script automatically builds up a ssh connection to the web servers which hosts the website behind the domain.
Here one has the choice whether one ssh or sshrc would like to use and also the possibility to customize the user to login.
As soon as all important data is given the connection to the server is erstablished.
Here the real function of the script appears, because the script automatically searches for the given domain and opens the right Documentroot and passes the control of the shell to the user.

OpenWeb works only with apache2.

The server is determined via DNS - if the domain is behind a proxy, the script is currently not working.

Pull requests are welcome.

### Usage
```
ow www.google.com
```
![Demo](https://raw.githubusercontent.com/iMi-digital/tools/master/doc/ow-demo.gif)
