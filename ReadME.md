

## Verify driver NVIDIA

> nvidia-smi

### Install driver, wether isn't installed:

> Download driver

> chmod +x yourfilename. run

</br>


### Extensions to install

<br>

- [**Sound Input & Output Device Chooser**](https://extensions.gnome.org/extension/906/sound-output-device-chooser)


<br>

Config default:

!["texto"](/img/2023-03-03_20-21.png)

---

- [**Extension List**](https://extensions.gnome.org/extension/3088/extension-list/)



# Apps Default

## Google Chrome

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo apt install .\google-chrome-stable_current_amd64.deb
```
<br>


## ZSH
https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH

<br>

```
apt install zsh
```
<br>

## Oh-My-Zsh
*https://ohmyz.sh/#install*
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```

> **Logout to save this installation**

<br>

## Brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"


echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/$USER/.profile

eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
```
##

<br>

## Flameshot

*https://flameshot.org/docs/installation/installation-linux/*
```
apt install flameshot
```
<br>

## Htop


``` 
sudo apt install htop 
``` 
<br>

# Apps to Work/Study

## Visual Studio Code

*https://code.visualstudio.com/docs/setup/linux*
```
sudo apt-get install wget gpg

wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg

sudo install -D -o root -g root -m 644 packages.microsoft.gpg /etc/apt/keyrings/packages.microsoft.gpg

sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'

rm -f packages.microsoft.gpg
```
<br>

## Terraform
*https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli*

```
sudo apt-get update && sudo apt-get install -y gnupg software-properties-common

wget -O- https://apt.releases.hashicorp.com/gpg | \
    gpg --dearmor | \
    sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg

echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] \
    https://apt.releases.hashicorp.com $(lsb_release -cs) main" | \
    sudo tee /etc/apt/sources.list.d/hashicorp.list

sudo apt update

sudo apt-get install terraform

terraform -help
```
## Tfvars
*https://github.com/tfutils/tfenv*

```
brew install tfenv
```
## Kubectl
https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-kubectl-binary-with-curl-on-linux

```
brew install kubectl
```
## Docker
https://docs.docker.com/engine/install/ubuntu/


