# LNPP Stack Scripts

Scripts to simplify installing, configuring, and maintaining nginx, php-fpm, and postgres on ubuntu.
Tested on ubuntu 12.10.

## Digital Ocean

You can use these scripts to setup your Digital Ocean VPS. 

## Install Scripts

To download and use initial install scripts, use the following commands (as root):

```bash
wget https://raw.github.com/kha0s-tickler/lnppscripts/master/install-stack.sh
chmod u+x install-stack.sh
./install-stack.sh
```

## Helper Scripts

Helper scripts get installed to /usr/local/bin.

```bash
# create a site
site-create example.com

# install phpsecinfo in current directory
site-install-phpsecinfo

# delete a site
site-delete example.com

# disable a site
site-disable example.com

# enable a disabled site
site-enable example.com

# update helper scripts
sudo lnpp-helpers update
```

## Warranty

None, use at your own risk!

## License
a fork from http://github.com/gizmovation/lnppstack for linode VPS

[MIT](http://opensource.org/licenses/MIT) 
