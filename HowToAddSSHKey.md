# How to add ssh key to Github
##  On [Google cloud shell](https://shell.cloud.google.com/?hl=en_US&fromcloudshell=true&show=terminal#id=I0_1615464799627&_gfid=I0_1615464799627&parent=https://console.cloud.google.com&pfname=&rpctoken=42806127)
* ssh-key generate command
```bash
ssh-keygen 
```
* The ssh-keygen program will show you for the location of the key file. Press Enter to accept defaults. The output of the program will look similar to this:
```
Generating public/private rsa key pair.
Enter file in which to save the key (/home/nirawat_fuse/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/nirawat_fuse/.ssh/id_rsa.
Your public key has been saved in /home/nirawat_fuse/.ssh/id_rsa.pub.
```
* View publlic key
```bash
cat ~/.ssh/id_rsa.pub
# Copy your public key
```
## Add your public key to GitHub
* Go to <https://github.com> Sign up and login with your credential
* Go to <https://github.com/settings/keys> or menu Settings on your avatar icon on the top right and choose menu SSH and GPG keys on the left
* Click on `New SSH key`
![Imgur](https://i.imgur.com/vvz54U8.png)

* Put `Title` of your public key and your key on the `Key` textbox and click `Add SSH key`
![Imgur](https://i.imgur.com/JJ5Ybxe.png)

* The Website look similar to this
![Imgur](https://i.imgur.com/pfWeJ2y.png)