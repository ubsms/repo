# UBSMS Apt repository

## Configuring the repostitory

Please run the following to set it up:

### Ubuntu

```
sudo apt update
sudo apt -y install apt-transport-https lsb-release
echo 'deb https://ubsms.github.io/repo/ubuntu '$(lsb_release -cs)' main' | sudo tee --append /etc/apt/sources.list.d/ubsms.list
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv 2B6C24A2
```
