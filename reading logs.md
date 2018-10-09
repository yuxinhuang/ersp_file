Man is to Computer Programmer as Woman is to homemaker?
Part 1

After reading the abstraction:
The main problem the paper is solving: Gender bias that word embedding has.
Main contribution of the paper: debias the embeddings and prevent amplifying gender bias in the real world.

After reading the introduction:
Bias :

1. Location of vector 

2. Gender stereotype

The main problem is that word embeddings have gender bias hence introducing bias to the real-world. Gender bias in word embeddings are usually cause by either the location of the word vector or gender stereotype in the real world.

I am confused about how to define the vector. What stands for their direction? What stands for their length? The question is one of the basis of word embeddings.

After reading the results section:

The author sets examples to show that their debias algorithms works. 

For Direct Bias, consider the analogy puzzle, he to doctor as she to X. After debias, X would be physician instead of nurse. For Indirect Bias, the relevance between receptionist and softball etc. are removed. What is more, the appropriate analogies are not removed or changed after the debias algorithm.

It is compelling because they demonstrate graphs to collect all the instances, comparing the gender bias in word embeddings before and after their debias algorithms. 


Related work:

It can be divided into bias in language and bias in algorithm

  Bias in language:
    Benevolent sexism
    Complementary 
    
  Bias in algorithm:
    Schmidt tries to remove gender from word embeddings. Yet what he focuses is one fair classification, and we should have a     clear classification and the problem is exacerbate by indirect bias

Reading the “meat”:
What the paper proposed:

A.Define gender subset g

B.We can divide bias into direct and indirect bias. 

  For for both direct and indirct bias (direct: usually gender specific words and gender neutral words eg. grandma. indirect: softball), the gender bias can be calculated
  
  In debiasing algorithm, we should first identify gender subspace, then neutralized and soften the subspace. Eventually we do soft bias correction.
  
Questions:

I do not understand the algorithms of Indirect bias and debiasing algorithm. It is linear algebra
Does equalizing in the debiasing algorithms mean for example make softball-football=0?
The larger S(a,b) is, the more gender direction a-b has?

