Bootstrap: docker
From: ubuntu:16.04

%post
    apt-get -y update
    apt-get -y install fortune cowsay lolcat figlet

%environment
    export LC_ALL=C
    export PATH=/usr/games:$PATH

%runscript
    figlet "JHPCE" | cowsay | lolcat
