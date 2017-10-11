# syntax-highlighter
syntax highlighter for my personal blogs

Generate custom .js and .css files 
<pre>
git clone https://github.com/syntaxhighlighter/syntaxhighlighter.git .
npm install
gulp setup-project
gulp build --brushes=css,bash,javascript,java,xml,typescript,sass --theme=default
</pre>

Insert into Blogger Template ie Design just before end of &lt;/head&gt; tag 
<!-- Begin SyntaxHighlighter-->

<script src='https://cdn.rawgit.com/condorgeek/syntax-highlighter/4c67b869/syntaxhighlighter.js' type='text/javascript'/>
<link href='https://cdn.rawgit.com/condorgeek/syntax-highlighter/4c67b869/theme.css' rel='stylesheet' type='text/css'/>

<!-- End SyntaxHighlighter-->

For detailed instructions on setting up this files into Blogger visit my blog under https://webzbuzz.blogspot.co.uk/
