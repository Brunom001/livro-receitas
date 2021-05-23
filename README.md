#livro de receitas :man_cook:

ola bem vindo

   ##Pave






#!/bin/bash

##Shell Script para instalação no Linux Ubuntu ##

sudo rm /var/lib/dpkg/lock-frontend ; sudo rm /var/cache/apt/archives/lock ;

## Atualizando Repositório ##

sudo apt update

## Downloads de programas externos ##

mkdir /home/$USER/Downloads/programas

cd /home/$USER/Downloads/programas

## Navegador Chrome ##

wget -c https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

## Zoom ##

wget -c https://cdn.zoom.us/prod/5.6.16888.0424/zoom_amd64.deb

## WPS - Office ##

wget -c https://wdl1.pcfg.cache.wpscdn.com/wpsdl/wpsoffice/download/linux/10161/wps-office_11.1.0.10161.XA_amd64.deb

sudo dpkg -i*.deb

## Instalando Programas via Terminal ##

sudo snap install spotify -y

sudo apt update

sudo snap install -y 

sudo apt update

sudo apt-get install deluge -y

sudo apt update

sudo snap install pycharm-community --classic -y

sudo apt update

sudo snap install code -classic -y

sudo apt update

sudo snap refresh code -y

sudo apt update

sudo snap install discord -y

sudo snap install telegram-desktop -y
 
sudo snap install snap-store -y

sudo apt install ubuntu-restricted-extras -y

sudo apt install winff -y

sudo apt install virtualbox -y

sudo apt update
