#Bootstrap Customize Boilerplate

A boilerplate installation of Bootstrap Sass.



##### Install with RVM
https://rvm.io/rvm/security

Add to .bash_profile
```
#Source from other bash profiles
if [ -r ~/.profile ]; then . ~/.profile; fi
case "$-" in *i*) if [ -r ~/.bashrc ]; then . ~/.bashrc; fi;; esac
```

```
#Install gpg
brew install gpg

# Install mpapis public key (might need `gpg2` and or `sudo`)
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3

#Install Stable RVM
\curl -sSL https://get.rvm.io | bash -s stable --ruby

#Set source of RVM to home
echo "source $HOME/.rvm/scripts/rvm" >> ~/.bash_profile

rvm rubygems latest

gem install compass

```

```
gem update --system && gem install compass
````