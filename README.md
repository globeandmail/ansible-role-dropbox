# Dropbox for Ubuntu

## This will download the headless bundle from Dropbox, and install it under ~{{dropbox_install_user}}/.dropbox-dist/

## Please note that this role will output a URL that you must visit within 3 minutes to connect a Dropbox account to the target host.

Default Vars:
-------------
- dropbox_download_url: "https://www.dropbox.com/download?plat=lnx.x86_64"
- dropbox_install_user: "dropbox"