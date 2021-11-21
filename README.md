# Quadriga Install Instructions

## macOS 

`brew tap stefangrosaru/quadriga`

`brew install quadriga`


## Debian/Ubuntu

`curl -sL https://apt.quadriga.cf/gpgkey | sudo apt-key add -`

`echo "deb [arch=amd64] https://apt.quadriga.cf stable main" | sudo tee /etc/apt/sources.list.d/quadriga.list`

`sudo apt update`

`sudo apt install quadriga`