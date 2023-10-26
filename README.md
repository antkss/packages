### packages
## built packages for archlinux
if the package has size more than 100MB, i'll be manually download because of some github limit reasons, I don't have money to pay for a better one 
## how to add repo to pacman ?
- add these lines to pacman.conf:
[antk]
Server = https://antkss.github.io/packages
- Uncomment and correct these lines become to this
  
SigLevel    = Optional
RemoteFileSigLevel = Optional
  
