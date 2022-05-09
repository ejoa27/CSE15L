# CSE15L Lab Report 3
# Streamlining ssh Configuration
I edited my config file by creating a config file0 in the .ssh folder of my user account folder, and writing the necessary alias in the config file. This allowed me to login into my ieng6 account without having to my complete username:
![Config](Images/configLab3.png)
![Login](Images/loginLab3.png)
![Copy](Images/copyLab3.png)

# Setup Github Access from ieng6
In Github, the public key is stored in the SSH and GPG keys section of the settings:
![PublicKey](Images/PublicKeyLab3.png)
In my user account, the public key is located in a file called id_rsa.pub, and the private key is located in a file called id_rsa. Both are stored in the .ssh directory.
![PrivateKey](Images/PrivateKeyLab3.png)

![editLab3](Images/editLab3.png)
![AddAndCommit](Images/AddAndCommit.png)

# Copy whole directories with `scp -r`
