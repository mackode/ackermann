# Ackermann function

The Ackermann function is a classic example of a recursive function, notable especially because it is not a primitive recursive function. It grows very quickly in value and also the size of its call tree.


The Ackermann function is usually defined as follows:


{\displaystyle A(m,n)={\begin{cases}n+1&{\mbox{if }}m=0\\A(m-1,1)&{\mbox{if }}m>0{\mbox{ and }}n=0\\A(m-1,A(m,n-1))&{\mbox{if }}m>0{\mbox{ and }}n>0.\end{cases}}}


Its arguments are never negative and it always terminates.
