# DirectAdmin Blesta Direct Login
Module modification to allow the user to sign-in directly to DirectAdmin without having to enter there username and password for DirectAdmin.

## Installation
Assuming you have made no other modifications to this file (unlikely).
> /path-to-blesta-installation/components/modules/direct_admin/views/default/client_service_info.pdt
  
Replace it with the contents of [client_service_info.pdt](https://github.com/blestamodules/directadmin-form-based-login/blob/master/client_service_info.pdt) 

## Limitations
Currently if a user changes there password in directadmin, they cannot use this function it will just take them to the directadmin login screen.

Your DirectAdmin installation should use SSL - otherwise this will just take them to the login screen.

## The Future
I will make a service tab when they click on "manage" in the next update.

Want to be updated? Join [my discord](https://discord.gg/azt7fEB) otherwise hit the "watch" button here.

I have always had plans to create a "DirectAdmin Extended" which will be a paid module option, I'm not very familiar with Blesta however so by me expirementing with DirectAdmin now It will lead me on my journey.



