# Selected works
A compilation.

[Link to PDF](https://github.com/DylanLawless/selectedworks/blob/master/latex/selectedworks.pdf)

# pull

``` bash 
## Set up the ssh config file
cd ~/.ssh/config

## set such that Host and User are custom
# lawlessgenomics repo
Host dylanlawless.github.com
  HostName github.com
  User DylanLawless
  PreferredAuthentications publickey
  IdentityFile ~/.ssh/key1_rsa
  IdentitiesOnly yes
# Clone using the correct Host as per config.
git clone git@dylanlawless.github.com:DylanLawless/selectedworks.git

# Set the local user here (instead of global, i.e. /Users/user/.gitconfig)
cd "the clone repo dir"
git config user.email personemail@addess.com
git config user.name DylanLawless
```
