## Switch ... Case --->



``` 
: X 

			dup 2 =   	->  "Two!"    	  |
			
		        dup 3 =   	->  "Three!"  	  |
		
			    4 =   	->  "Four!"  	  |
		
		         otherwise  	    "Whatever"    |.
			. cr 
		;
 ``` 
    
In this case,dup serve as case ,:X serve as switch


## If...else --->
``` 
:  two  
			    2 = IF  
			    	"Yes, this is two! :)" 
			    ELSE  
			    	"No, this is not two. :(" 
			    THEN . cr
			;
```

## Printf --->
```
"XXX" .
```

## 1 +1 -->
```
1 2 + .
```
Note ,when doing float ,use .. like 1 2 / ..

## using a module
```
: Action
"Finding area,enter 2 number \n" .
* .
 ;
5 6 Action 
```
## if (strcmp(s1,s2)==1) ===>
```
"hi"=>s1
"bye"=>s2
"s1" "s2" SAME? .
```
## a=1; ===>
```
"1"=>a
