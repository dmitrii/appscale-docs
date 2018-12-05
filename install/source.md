In a clean **Ubuntu 16.04 (Xenial Xerus)** virtual machine, begin by running the following:
```
sudo su
export HOME=/root
wget -O bootstrap.sh http://bootstrap.appscale.com
bash bootstrap.sh
```
The AppScale bootstrap script installs git and clones AppScale and AppScale Tools repos.
It then installs AppScale and AppScale Tools by executing the build scripts for each.

For more options, run 
```
bash bootstrap.sh --help
```
