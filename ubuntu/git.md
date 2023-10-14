# GIT

## Install GIT
````
sudo apt install git;
````
## Generate SSH

````
ssh-keygen -t ed25519 -C "your_email@example.com";
eval "$(ssh-agent -s)";
ssh-add ~/.ssh/id_ed25519;
````

# Clone
````
git clone git@github.com:oscardasilva0/repositorio.git  ./pasta_destino/;
````
