# Magic Wonders Here 
Including all these helpful tricks to debug annoying hurdles I face with Linux/Ubuntu:3 

## sudo apt update on ubuntu gives "invalid repositories"
**solution** : try this on the cmd
````
sudo apt-get clean
cd /var/lib/apt
sudo mv lists lists.old
sudo mkdir -p lists/partial
sudo apt-get clean
sudo apt-get update
````
