# Installing Node.js via package manager (ubuntu)

https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

**NOTE:** If you are using Ubuntu Precise or Debian Wheezy, you might want to read about [running Node.js >= 6.x on older distros](https://github.com/nodesource/distributions/blob/master/OLDER_DISTROS.md).

     curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
     sudo apt-get install -y nodejs
     
 
Alternatively, for Node.js 10:
 
     curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
     sudo apt-get install -y nodejs
     
 
**_Optional_**: install build tools
 
 To compile and install native addons from npm you may also need to install build tools:
 
     sudo apt-get install -y build-essential
