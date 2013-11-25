iamsese.unicode
===============

iamsese.unicode.php

```

IAMSESE_UNICODE::test();
//IAMSESE_UNICODE::echoUnicodeTable();
IAMSESE_UNICODE::echoAsciiTable();


	function test(){
		$test1 ='我是色色[iamsese.cn] начинается уже в марте bbs.cn #$%^&*()_+!@QADD?><.,,m';
		$test1 = IAMSESE_UNICODE::encode($test1);
		echo $test1 ;
		echo "\n<br/>\n";
		$test1 = IAMSESE_UNICODE::deUnicode($test1);
		echo $test1 ;		
	}
	
	test();
```




