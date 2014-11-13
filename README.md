vim
===

Cool Awesome Vim Stuff!

http://joshmccall221.github.io/vim/



    <div class="container">
      <section id="main_content">
        <h1>
<a id="vim" class="anchor" href="#vim" aria-hidden="true"><span class="octicon octicon-link"></span></a>vim</h1>

<p>Cool Awesome Vim Stuff!</p>

<h4>
<a id="setup-vim-74" class="anchor" href="#setup-vim-74" aria-hidden="true"><span class="octicon octicon-link"></span></a>Setup: Vim 7.4</h4>

<p>brew install vim</p>

<p>If you have multiple VIM versions installed, or you can not invoke vim from the command line:</p>
		
<pre>
echo 'export PATH="/usr/local/bin:$PATH"' &gt;&gt; .bashrc
</pre>

<h3>
Pathogen Installation
</h3>

<p>Install to <code>~/.vim/autoload/pathogen.vim</code>.  Or copy and paste:</p>

<pre><code>mkdir -p ~/.vim/autoload ~/.vim/bundle &amp;&amp; \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
</code></pre>


<h4>
<a id="git" class="anchor" href="#git" aria-hidden="true"><span class="octicon octicon-link"></span></a>Git:</h4>

<blockquote>

<h4>
<a id="note" class="anchor" href="#note" aria-hidden="true"><span class="octicon octicon-link"></span></a>note:</h4>

<p>Vim 7.4 introduced a new, very useful, scheme: it looks for the usual ~/.vimrc and also for ~/.vim/vimrc so that's even less work for you:
<a href="http://stackoverflow.com/questions/18197705/adding-your-vim-vimrc-to-github-aka-dot-files/18203545#18203545">http://stackoverflow.com/questions/18197705/adding-your-vim-vimrc-to-github-aka-dot-files/18203545#18203545</a></p>
</blockquote>


<pre>
```bash
$mv ~/.vim/.vimrc ~/.vim/vimrc
$ cd .vim
$ git init
$ echo "This is my Vim config." &gt; README
$ git add *
$ git commit -m "My Vim config is versioned."
$ git remote add origin <a href="https://github.com/username/vimconfig.git">https://github.com/username/vimconfig.git</a>
$ git push origin master
```
</pre>
</br>
</br>
</br>
<h5>Mentions and Ueseful links:</h5>
<p>
VimAwesome:<a href="http://vimawesome.com/plugin/the-nerd-tree">link</a><br/>
 vimcasts.org sync plugins with git submodules and Pathogen:<a href="http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/">link</a>
 <p/>
      </section>
    </div>
