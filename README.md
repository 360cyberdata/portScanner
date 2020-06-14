# portScanner
Build you your own tools

Installing Go
On your Linux server, in a Terminal window, execute these commands:

sudo apt update
sudo apt install curl -y

curl -O https://dl.google.com/go/go1.13.3.linux-amd64.tar.gz
sha256sum go1.13.3.linux-amd64.tar.gz

tar xvf go1.13.3.linux-amd64.tar.gz
sudo chown -R root:root ./go
sudo mv go /usr/local
echo export GOPATH=$HOME/work >> ~/.profile
echo export PATH=\$PATH:/usr/local/go/bin:\$GOPATH/bin >> ~/.profile
source ~/.profile
go

mkdir $HOME/work
mkdir -p work/src/my_project/360cyberdata
nano ~/work/src/my_project/360cyberdata/360cyberdata.go

go install my_project/360cyberdata
hello
