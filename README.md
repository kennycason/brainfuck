brainfuck
=========

BrainF***
http://ken-soft.com/2011/01/14/brainfuck-programming-language-minor-varient/

brainfuck command 	C equivalent
```
> 	++CP;
< 	–CP;
+ 	++*CP;
- 	–*CP;
[ 	while (*CP) {
] 	}
c 	printf(“%c”,(char)*CP)
d 	printf(“%u”,*CP);
C 	while (scanf(“%c”, CP) != 1);
D 	while (scanf(“%u”, CP) != 1);
M 	Print out Cell and Pointers
I 	Print out Instruction Pointer
```

CP is the Cell Pointer

Hello World.bf
```
+++++ +++++
[
    > +++++ ++
    > +++++ +++++
    > +++
    > +
 
    <<<< -
]
> ++ .
> + .
+++++ ++ .
.
+++ .
> ++ .
<< +++++ +++++ +++++ .
> .
+++ .
----- - .
----- --- .
> + .
> .
M
```
