# ASCII Gradient Generator
https://www.reddit.com/r/dailyprogrammer/comments/3104wu/20150401_challenge_208_intermediate_ascii/

Look at the ascii-gradient.c file for more or less proper documentation.

## Python
```sh
$ cd ascii-gradient
$ cat samples/sample.txt | python python/ascii-gradient.py 
@ @ @ @ @ @ @ @ @ @ @ & & & & & X X X X X X X X X & & & & & @ @ @ @ @ @ @ @ @ @ 
@ @ @ @ @ @ @ @ @ @ & & & & X X X X X X X X X X X X X & & & & @ @ @ @ @ @ @ @ @ 
@ @ @ @ @ @ @ @ & & & & X X X X X X x x x x x X X X X X X & & & & @ @ @ @ @ @ @ 
@ @ @ @ @ @ @ & & & & X X X X x x x x x x x x x x x X X X X & & & & @ @ @ @ @ @ 
@ @ @ @ @ @ @ & & & X X X x x x x x x ; ; ; x x x x x x X X X & & & @ @ @ @ @ @ 
@ @ @ @ @ @ & & & X X X x x x x ; ; ; ; ; ; ; ; ; x x x x X X X & & & @ @ @ @ @ 
@ @ @ @ @ & & & X X X x x x ; ; ; ; ; ; ; ; ; ; ; ; ; x x x X X X & & & @ @ @ @ 
@ @ @ @ @ & & X X X x x x ; ; ; ; : : : : : : : ; ; ; ; x x x X X X & & @ @ @ @ 
@ @ @ @ & & & X X x x x ; ; ; : : : : : : : : : : : ; ; ; x x x X X & & & @ @ @ 
@ @ @ @ & & X X X x x ; ; ; : : : : , , , , , : : : : ; ; ; x x X X X & & @ @ @ 
@ @ @ & & & X X x x x ; ; : : : , , , , , , , , , : : : ; ; x x x X X & & & @ @ 
@ @ @ & & X X X x x ; ; ; : : , , , , . . . , , , , : : ; ; ; x x X X X & & @ @ 
@ @ @ & & X X X x x ; ; : : : , , . . . . . . . , , : : : ; ; x x X X X & & @ @ 
@ @ @ & & X X x x x ; ; : : , , , . . .   . . . , , , : : ; ; x x x X X & & @ @ 
@ @ @ & & X X x x ; ; ; : : , , . . .       . . . , , : : ; ; ; x x X X & & @ @ 
@ @ @ & & X X x x ; ; ; : : , , . .           . . , , : : ; ; ; x x X X & & @ @ 
@ @ @ & & X X x x ; ; ; : : , , . . .       . . . , , : : ; ; ; x x X X & & @ @ 
@ @ @ & & X X x x x ; ; : : , , , . . .   . . . , , , : : ; ; x x x X X & & @ @ 
@ @ @ & & X X X x x ; ; : : : , , . . . . . . . , , : : : ; ; x x X X X & & @ @ 
@ @ @ & & X X X x x ; ; ; : : , , , , . . . , , , , : : ; ; ; x x X X X & & @ @ 
@ @ @ & & & X X x x x ; ; : : : , , , , , , , , , : : : ; ; x x x X X & & & @ @ 
@ @ @ @ & & X X X x x ; ; ; : : : : , , , , , : : : : ; ; ; x x X X X & & @ @ @ 
@ @ @ @ & & & X X x x x ; ; ; : : : : : : : : : : : ; ; ; x x x X X & & & @ @ @ 
@ @ @ @ @ & & X X X x x x ; ; ; ; : : : : : : : ; ; ; ; x x x X X X & & @ @ @ @ 
@ @ @ @ @ & & & X X X x x x ; ; ; ; ; ; ; ; ; ; ; ; ; x x x X X X & & & @ @ @ @ 
@ @ @ @ @ @ & & & X X X x x x x ; ; ; ; ; ; ; ; ; x x x x X X X & & & @ @ @ @ @ 
@ @ @ @ @ @ @ & & & X X X x x x x x x ; ; ; x x x x x x X X X & & & @ @ @ @ @ @ 
@ @ @ @ @ @ @ & & & & X X X X x x x x x x x x x x x X X X X & & & & @ @ @ @ @ @ 
@ @ @ @ @ @ @ @ & & & & X X X X X X x x x x x X X X X X X & & & & @ @ @ @ @ @ @ 
@ @ @ @ @ @ @ @ @ @ & & & & X X X X X X X X X X X X X & & & & @ @ @ @ @ @ @ @ @ 
```

## C
```sh
$ cd ascii-gradient
$ gcc c/ascii-gradient.c 
$ cat samples/sample2.txt | ./a.out 
$$$$$$$$$$$+++++++++^^^^^^^^^^^"""""""""''''''''''          
$$$$$$$$$$++++++++++^^^^^^^^^^"""""""""'''''''''''          
$$$$$$$$$++++++++++^^^^^^^^^^""""""""""'''''''''            
$$$$$$$$+++++++++^^^^^^^^^^^"""""""""'''''''''''            
$$$$$$$+++++++++^^^^^^^^^^^"""""""""''''''''''              
$$$$$$+++++++++^^^^^^^^^^^"""""""""''''''''''               
$$$$$+++++++++^^^^^^^^^^^"""""""""''''''''''                
$$$$+++++++++^^^^^^^^^^^""""""""""'''''''''                 
$$$+++++++++^^^^^^^^^^^""""""""""''''''''''                 
$$+++++++++^^^^^^^^^^^""""""""""''''''''''                  
$++++++++++^^^^^^^^^^"""""""""'''''''''''                   
+++++++++^^^^^^^^^^^"""""""""'''''''''''                    
++++++++^^^^^^^^^^^""""""""""'''''''''                      
+++++++^^^^^^^^^^^"""""""""''''''''''                       
++++++^^^^^^^^^^^"""""""""''''''''''                        
+++++^^^^^^^^^^^"""""""""''''''''''                         
++++^^^^^^^^^^^""""""""""''''''''''                         
+++^^^^^^^^^^^""""""""""''''''''''                          
+++^^^^^^^^^^""""""""""''''''''''                           
++^^^^^^^^^^""""""""""''''''''''                            
^^^^^^^^^^^"""""""""'''''''''''                             
^^^^^^^^^^""""""""""'''''''''                               
^^^^^^^^^""""""""""'''''''''                                
^^^^^^^^""""""""""''''''''''                                
^^^^^^^""""""""""''''''''''                                 
^^^^^^"""""""""'''''''''''                                  
^^^^^"""""""""'''''''''''                                   
^^^^"""""""""'''''''''''                                    
^^^""""""""""'''''''''                                      
^^"""""""""''''''''''     
```

## Java
```sh
$ cd ascii-gradient/java
$ javac AsciiGradient.java
$ cat ../samples/sample3.txt | java AsciiGradient
ccccccccccdddddeeeeeeeeeeeeeeeffffgggggg
cccccccccccdddddeeeeeeeeeeeeeefffffggggg
ccccccccccccdddddeeeeeeeeeeeeeeffffggggg
cccccccccccccdddddeeeeeeeeeeeeeffffggggg
cccccccccccccdddddeeeeeeeeeeeeefffffgggg
ccccccccccccccdddddeeeeeeeeeeeeeffffgggg
cccccccccccccccddddeeeeeeeeeeeeeffffgggg
cccccccccccccccdddddeeeeeeeeeeeeeffffggg
bcccccccccccccccddddeeeeeeeeeeeeeffffggg
bbccccccccccccccdddddeeeeeeeeeeeeffffggg
bbbccccccccccccccddddeeeeeeeeeeeeffffggg
bbbbcccccccccccccddddeeeeeeeeeeeeeffffgg
bbbbcccccccccccccddddeeeeeeeeeeeeeffffgg
bbbbbcccccccccccccddddeeeeeeeeeeeeffffgg
abbbbcccccccccccccddddeeeeeeeeeeeeffffgg
abbbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
aabbbbccccccccccccddddeeeeeeeeeeeeffffgg
abbbbbccccccccccccddddeeeeeeeeeeeeffffgg
abbbbcccccccccccccddddeeeeeeeeeeeeffffgg
bbbbbcccccccccccccddddeeeeeeeeeeeeffffgg
bbbbcccccccccccccddddeeeeeeeeeeeeeffffgg
bbbbcccccccccccccddddeeeeeeeeeeeeeffffgg
bbbccccccccccccccddddeeeeeeeeeeeeffffggg
bbccccccccccccccdddddeeeeeeeeeeeeffffggg
bcccccccccccccccddddeeeeeeeeeeeeeffffggg
cccccccccccccccdddddeeeeeeeeeeeeeffffggg
cccccccccccccccddddeeeeeeeeeeeeeffffgggg
ccccccccccccccdddddeeeeeeeeeeeeeffffgggg
cccccccccccccdddddeeeeeeeeeeeeefffffgggg
cccccccccccccdddddeeeeeeeeeeeeeffffggggg
ccccccccccccdddddeeeeeeeeeeeeeeffffggggg
cccccccccccdddddeeeeeeeeeeeeeefffffggggg
```



