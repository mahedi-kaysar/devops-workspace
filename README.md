# devops-workspace
This repo is to track some usefull stuff necessary while in development

## Install Intellij on CentOS

[visit] https://www.javahelps.com/2015/04/install-intellij-idea-on-ubuntu.html

## Generate SSH Public Key for GIT in linux

Access keys provide a simple way for other systems to access repositories using SSH without storing user credentials.

```
ssh-keygen
cat /home/$USER/.ssh/id_rsa.pub
```

Copy the public key to git's access key section.

