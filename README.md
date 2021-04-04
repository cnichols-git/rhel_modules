# rhel_modules

## Redhat 8 has implemented something called modules

I struggled to get httpd installed on a developer RHEL 8 subscriprion and had to use the following to get the software installed

yum module list httpd - this will provide you with the info on how to get the software/module installed

yum module install httpd:2.4/common

appstream
Name                                  Stream                                  Profiles                                                  Summary                                          
httpd                                 2.4 [e]                                 default, devel, minimal                                   Apache HTTP Server                               

Red Hat Enterprise Linux 8 for x86_64 - AppStream (RPMs)
Name                                  Stream                                  Profiles                                                  Summary                                          
httpd                                 2.4 [e]                                 common [i], devel, minimal                                Apache HTTP Server 

module : httpd
stream : 2.4 
profile: common

yum module install httpd:2.4/common - this will install the software
