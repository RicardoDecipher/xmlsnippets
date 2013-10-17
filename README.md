<p>This is the latest Decipher XML snippets file.  It includes quick snippets to allow you to code your surveys faster in Beacon.</p>

<p>It is required that you have the vim <a href="https://github.com/msanders/snipmate.vim" target="_blank">snipmate</a> plugin installed.</p>

<p>To install this file, run the below command:</p>

<code>wget -O ~./vim/snippets/xml.snippets https://raw.github.com/minhdecipher/xmlsnippets/master/xml.snippets</code>
<p>Note: This will overwrite your current snippets file!</p>

<p>To see all the snippet keywords, type the below command:</p>
<code>grep 'snippet' ~/.vim/snippets/xml.snippets | cut -d" " -f 2 | vim -</code>

<p>This will open up in a vim session for you to view.</p>

<p>Snippet Usage:</p>
<code>snippetkeyword &lt;tab-key&gt;</code>
<p>NOTE: Your insert mode must not be in paste mode!</p>
<p>Easy way to get around this is to have a toggle that quickly changes this.  Add the below to your .vimrc</p>

<code>set pastetoggle=&lt;F3&gt;</code>
