vim
===

Cool Awesome Vim Stuff!


####Setup: Vim 7.4 
brew install vim

If you have multiple VI/VIM versions installed, or you can not invoke vim from the command line:
echo 'export PATH="/usr/local/bin:$PATH"' >> .bashrc


####Git: 
>####note:
>Vim 7.4 introduced a new, very useful, scheme: it looks for the usual ~/.vimrc and also for ~/.vim/vimrc so that's even less work for you:  
>http://stackoverflow.com/questions/18197705/adding-your-vim-vimrc-to-github-aka-dot-files/18203545#18203545

'''bash
$mv ~/.vim/.vimrc ~/.vim/vimrc  
$ cd .vim  
$ git init  
$ echo "This is my Vim config." > README  
$ git add *  
$ git commit -m "My Vim config is versioned."  
$ git remote add origin https://github.com/username/vimconfig.git  
$ git push origin master  
'''
