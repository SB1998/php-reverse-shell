# php-reverse-shell


# Edits to original
- Changed IP and Port in reverse shell
- Created obfuscated version with base64 encoding

Info to base64 Version:
- I used https://www.base64encode.org/ for encoding
- the <?php and ?> are removed before encoding for eval(...) to work (see: https://www.php.net/manual/de/function.eval.php)
