# syntax-highlighter
syntax highlighter for my personal blogs

Insert into Blogger Template ie Design just before </head> tag 
<!-- Begin SyntaxHighlighter-->
    <link href='https://github.com/condorgeek/syntax-highlighter/blob/master/theme.css' rel='stylesheet' type='text/css'/>  
    <script src='https://github.com/condorgeek/syntax-highlighter/blob/master/syntaxhighlighter.js' type='text/javascript'/> 
       
    <script type='text/javascript'>
    window.setTimeout(function() {
        SyntaxHighlighter.config.bloggerMode = true;
        SyntaxHighlighter.all();
    }, 20);
    </script>
<!-- End SyntaxHighlighter-->
