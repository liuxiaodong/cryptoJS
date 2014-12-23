cryptoJS
========
<a href="https://github.com/calvinmetcalf/browserify-aes">browserify-aes</a>  
`<script type="text/javascript" src="cryptoJS.min.js"></script>`  
<pre><code>
  var cipher = cryptoJS.createCipheriv("aes-128-ecb", new buffer.Buffer("11223344556677889900aabbccddeeff","hex"), "");
  var result = cipher.update("aabbccddeeff112233");
  var final = cipher.final();
  result = buffer.Buffer.concat([result, final]);
</code></pre>
