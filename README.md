# Test

Here's my project where I do nothing but experience with Github. 

## Subheader
 
I do really want to learn version control systems.

# Commands 

- git status 

commit:

- git add .

- git commit -m "Added greeting.js" -m "Trying to make a commit"

generate ssh key localy":

- ssh-keygen -t rsa -b 4096 -C "ryabishcuk2@gmail.com"
- Enter file in which to save the key (/c/Users/Admin/.ssh/id_rsa): firstkey
- Enter passphrase (empty for no passphrase): 
- Enter same passphrase again:
- The key fingerprint is:
  SHA256:pHq4EvGUo0RETnzypaTnmPXK6XgHcryfERAhCiVK4YQ ryabishcuk2@gmail.com

- look for the key: 
  ls | grep firstkey
- print public key:
  cat firstkey.pub

- copy this public key and go to setting on github and click on new ssh key
    
- start the ssh-agent in the background: eval "$(ssh-agent -s)"

- then run from command line: ssh-add ~/.ssh/*nameoftheprivatekey*       
- enter passphrase

push: 

- git push origin main

# Featured Development

1. Praise your friends like in greeting.js