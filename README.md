<p>This is the latest Decipher XML snippets file.  It includes quick snippets to allow you to code your surveys faster in Beacon.</p>

<h3>Required:</h3>
<p>vim <a href="https://github.com/msanders/snipmate.vim" target="_blank">snipmate</a> plugin installed.</p>

<h3>Installation:</h3>
<p>Download the file to the appropriate snippets folder.  Run the below command:</p>

<code>wget -O ~/.vim/snippets/xml.snippets https://raw.github.com/minhdecipher/xmlsnippets/master/xml.snippets</code>
<p>Note: This will overwrite your current snippets file!</p>

<h3>Snippet Keywords:</h3>
<p>To see all the snippet keywords, type the below command:</p>
<code>grep 'snippet' ~/.vim/snippets/xml.snippets | cut -d" " -f 2 | vim -</code>
<p>This will open up in a vim session for you to view.</p>

<h3>Snippet Usage (any .xml file):</h3>
<code>snippetkeyword &lt;tab-key&gt;</code>
<p>NOTE: Your insert mode must not be in paste mode!</p>
<p>Easy way to get around this is to have a toggle that quickly changes this.  Add the below to your .vimrc</p>
<code>set pastetoggle=&lt;F3&gt;</code>
