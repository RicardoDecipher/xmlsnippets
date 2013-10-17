<p>This is the latest Decipher XML snippets file.  It includes quick snippets to allow you to code your surveys faster in Beacon.</p>

<p>It is required that you have the <a href="https://github.com/msanders/snipmate.vim" target="_blank">snipmate</a> plugin installed.</p>

Quickly install below:

git clone git://github.com/msanders/snipmate.vim.git
cd snipmate.vim
cp -R * ~/.vim


<p>To see all the snippet keywords, type the below command:</p>
<p>grep 'snippet' ~/.vim/snippets/xml.snippets | vim -</p>

<p>This will open up in a vim session for you to view.</p>

<p>Usage: snippetkeyword <tab-key></p>
<p>NOTE: Your insert mode must not be in paste mode!</p>
<p>Easy way to get around this is to have a toggle that quickly changes this.  Add the below to your .vimrc</p>

<p>set pastetoggle=<F3></p>
