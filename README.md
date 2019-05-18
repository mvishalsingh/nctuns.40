# nctuns.40
NCTUns-4.0 file which works with fedora 8 werewolf 32bit. Not compatible with fedora8 64bit. Read readme for entire method kn how to install. Used in Vtu networks lab subject code 10CSL77 2010 Scheme.

first download and install latest virtual box https://www.virtualbox.org/wiki/Downloads . i download.deb file and double clicked it install using GUI in linux mint. if you use software manager to install linux mint 19 chinnamon then the latest withh be 5.2 virtual box and it will have conflict when you install the latest virtual box extension pack https://download.virtualbox.org/virtualbox/6.0.8/Oracle_VM_VirtualBox_Extension_Pack-6.0.8.vbox-extpack
watch this video https://youtu.be/SQm0DxjLvFE.

For drag and drop you need to install virtual box guest addition,samba ,enable a share folder which will appear in /root/media
samba allows you to transfer your files in VM through virtual network in case of VM But it is the same as how you would transfer in reat pc remotely. too difficult for newbies won't recommend.

virtual box Extension Pack should be installed before proceeding further is need to detect usb pendrive and external hard drive through usb. if there is error check if the virtual box version is compatible with the extension pack your are installing.

remove previous virtual box to have no conflict,i even installed all my previous VM iso.

then go to setting virtual setting >usb setting>see if virtual bix detecting external hardrive. my pendrive didn't connect through it is detected,i think it may be due to format of the usb which is NTFS which i think may not be compatible with fedora8 i864(32 bit,amd64 stands for 64bit.) gonna change to FAT32 format and see it it works.
select usb2.0 thats what work for my western digital external hardisk but not sub

if hardik is detected it will show new icon is desktop
