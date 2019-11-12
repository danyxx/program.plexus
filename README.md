Plexus
================
Acestream remade to work with AceProxy . Without AceProxy will not work. 
If you want to use it now - you can install AceProxy yourself using this instruction https://github.com/danyxx/program.plexus/wiki

How to make Acestream work on Coreelec, Libreelec (and Openelec) Amlogic based boxes (not android, linux)

 then

ssh -l root "coreelec IP" Password: coreelec

cd /storage

curl -LO https://archive.org/download/acestream-aml/acestream-aml.tgz

tar xopf acestream-aml.tgz

rm -f acestream-aml.tgz

reboot
