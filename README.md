#Create symbolic links
  ln -s ~/.vim/vimrc ~/.vimrc
  ln -s ~/.vim/gvimrc ~/.gvimrc
#Upgrading all bundled plugins
  git git submodule foreach git pull origin master
