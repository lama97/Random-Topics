# sudo apt update on ubuntu gives "invalid repositories"
**solution** : try this on the cmd
````
sudo apt-get clean
cd /var/lib/apt
sudo mv lists lists.old
sudo mkdir -p lists/partial
sudo apt-get clean
sudo apt-get update
````
