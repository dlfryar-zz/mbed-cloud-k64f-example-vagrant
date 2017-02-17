# Host System
MacOS

# Install Brew
http://brew.sh/

# Install Vagrant
brew install Caskroom/cask/vagrant

# Install Virtualbox

brew tap caskroom/cask

brew install brew-cask

brew cask install virtualbox

mkdir -p ~/Source/ && cd ~/Source

git clone https://github.com/dlfryar/mbed-cloud-k64f-example-vagrant.git && cd mbed-cloud-k64f-example-vagrant

# Start Vagrant env
vagrant up

vagrant ssh

cd /vagrant_home/Source/my_vagrant_instance

ls -la