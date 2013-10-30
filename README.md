#Checkout

  `git clone --recurse-submodules git@github.com:scorpio147wbh/dotvim.git`
#Create symbolic links

  `ln -s ~/.vim/vimrc ~/.vimrc`

  `ln -s ~/.vim/gvimrc ~/.gvimrc`
#Upgrading all bundled plugins

  `git submodule foreach git pull origin master`
