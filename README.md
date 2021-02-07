# Index Calculus
<img src=
"https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+In+this+short+note+we+will+discuss+the+discrete+logarithm+problem+and+also+look+at+an+implementation+of+a+few+probabilistic+algorithms+for+computing+discrete+logarithms.+These+algorithms+are+collectively+classified+as+index+calculus+algorithms.%0A%0AThe+problem+of+computing+discrete+logarithms+can+be+summarized+as+follows.+Letting+%24q%24+be+a+prime+power%2C+the+multiplicative+subgroup+%24%5Cmathbb%7BF%7D_q%5E%2A+%5Cleq+%5Cmathbb%7BF%7D_q%24+is+cyclic.+Elements+that+generate+this+cyclic+subgroup+are+called+primitive.+If+we+are+given+a+primitive+element+%24g+%5Cin+%5Cmathbb%7BF%7D_q%24+as+well+as+any+%24h+%5Cin++%5Cmathbb%7BF%7D_q%5E%2A%24%2C+then+the+discrete+logarithm+of+%24h%24+with+respect+to+%24g%24+is+the+integer+%24x%2C+0+%5Cleq+x+%5Cleq+q-1%24+such+that+%24g%5Ex+%3D+h%24.+We+will+denote+this+by+the+usual+%24x+%3D+%5Clog_g+h+%5Censpace%0A%5Cmod+q%24.+The+goal+is+to+find+this+%24x%24+given+%24q%2C+g%24+and+%24h%24.+%0A%0AWe+will+start+by+looking+at+some+naive+implementations+of+index+calculi+and+then+refine+our+approaches+in+later+sections.%0A%0A" 
alt="In this short note we will discuss the discrete logarithm problem and also look at an implementation of a few probabilistic algorithms for computing discrete logarithms. These algorithms are collectively classified as index calculus algorithms.

The problem of computing discrete logarithms can be summarized as follows. Letting $q$ be a prime power, the multiplicative subgroup $\mathbb{F}_q^* \leq \mathbb{F}_q$ is cyclic. Elements that generate this cyclic subgroup are called primitive. If we are given a primitive element $g \in \mathbb{F}_q$ as well as any $h \in  \mathbb{F}_q^*$, then the discrete logarithm of $h$ with respect to $g$ is the integer $x, 0 \leq x \leq q-1$ such that $g^x = h$. We will denote this by the usual $x = \log_g h \enspace
\mod q$. The goal is to find this $x$ given $q, g$ and $h$. 

We will start by looking at some naive implementations of index calculi and then refine our approaches in later sections.

">
