# Sheet 7

## Exercise 2
### a) 
**unsorted**   
$O_{worst} = O(n)$  
$O_{best} = O(1)$  
$O_{average} = O((n+1)/2) = O(n) $    

**sorted**   
$O_{worst} = O(log(n))$  
$O_{best} = O(1)$   
$O_{average} = O(1/2 * log(n)) = O(log(n))$


### b) 
$Q = \{1,2,3\}$    
$q_0 = 1$  
$F = 3$   
$\sum = \{0,1\}$
$$
\begin{align*}
\delta =& \{\\
        & (1,2,0,0, \rightarrow), \\
        & (1,2,1,1, \rightarrow),\\
        & (1,3,Null,Null, \bot),\\
        & (2,1,0,1, \rightarrow),\\
        & (2,1,1,0, \rightarrow),\\
        & (2,3,Null,Null, \bot) \\
        \}

\end{align*}$$


### c) 
because its the wrong direction. You need to map the already existing L to L'. 

### d) 
both in NP 
