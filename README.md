# nULLvIOD.github.io
test test
<input type="password" id="password">
<button class="decrypt">Decrypt</button>
<script>    
    var myEncryptedPage = '<html-string-pre-encrypted-with-your-password>';
    $('.decrypt').click(function(){
        var password = $('#password').val();
        // 'decrypt' tries to decrypt your string with the user provided password
        document.write(decrypt(myEncryptedPage, password));
    });
</script>
<head> 
  <title>this is a header</title>  
</head>

<body>This is the body</body>
