
## Import Method

<br>


## Windows to Linux connection to same user


STEP 1:

1.Login into PuTTY and type the command ssh-keygen -b 1024 -t rsa
2.With the help of cd .ssh/ change the directory
3.Use ls to list the files created on the server as: authorized_keys id_rsa id_rsa.pub known_hosts
4.To save the public key use cat id_rsa.pub and paste it in the authorized_keys file using vi authorized_keys  

STEP 2:

I1.n the 'Connection' -> 'SSH' -> 'Auth' category, browse and select the private key file you saved .
2.Save these settings if you want to use them again in the future.
3.Click 'Open' to establish the SSH connection to the server for keyless authentication.

## Windows to Linux connection to different user

<br>


### Linux to Linux connection to own user

<br>


### Linux to Linux connection to different user

<br>

