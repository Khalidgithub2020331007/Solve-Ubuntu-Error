# Solve-Ubuntu-Error
# sub-process /usr/bin/dpkg returned an error code (1)
    sudo mv /var/lib/dpkg/info /var/lib/dpkg/inf0_silent
    sudo mkdir /var/lib/dpkg/info
    sudo apt-get update
    sudo apt-get -f installsudo apt-get update
    sudo mv /var/lib/dpkg/info/* /var/lib/dpkg/info_silent
    sudo rm -rf /var/lib/dpkg/info
    sudo mv /var/lib/dpkg/info_silent /var/lib/dpkg/info
    sudo apt-get update





    
