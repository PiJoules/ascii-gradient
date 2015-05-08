# ASCII Gradient Generator
https://www.reddit.com/r/dailyprogrammer/comments/3104wu/20150401_challenge_208_intermediate_ascii/

## Python
```py
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