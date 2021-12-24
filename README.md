<div align="center">
<img src="https://expimont.com/expimont/img/source-file-symbol.png" height="300"/>

<br>

# 👩‍💻 Expimont challenge - reversed
Deobfuscated challenge of the [Expimont WAF JavaScript challenge](https://expimont.com/expimont/js/challenge.js)

</div>

## ⚙ How it works
The JS challenge sets a cookie based on `testcookie_enc_set`. It uses the value of `testcookie_enc_set` to call some functions and generate an object. This object is then passed to the decryption function to generate the cookie. Afterwards you get redirected to the page. The decryption object can be dumped at that point, just before the cookie is being set to statically generate the cookie.
