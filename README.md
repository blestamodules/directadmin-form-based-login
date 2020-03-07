# DirectAdmin Blesta Direct Login
Module modification to allow the user to sign-in directly to DirectAdmin without having to enter there username and password for DirectAdmin.

## Installation
Assuming you have made no other modifications to this file (unlikely).
> /<path-to-blesta-installation>/components/modules/direct_admin/views/default/client_service_info.pdt
  
Replace it with the contents of client_service_info.pdt 



## Limitations
Currently if a user changes there password in directadmin, they cannot use this function it will just take them to the directadmin login screen.

Your DirectAdmin installation should use SSL - otherwise this will just take them to the login screen.

