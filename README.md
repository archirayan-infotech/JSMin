# JSMin

```php
<?php
$data= file_get_contents("bootstrap.js");
include("Jsmin.php");
$minified=JSMin::minify($data);
  
?>
