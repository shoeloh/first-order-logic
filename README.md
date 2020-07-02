## ABOUT  
In this program I prove a logical statement given support from a corpus of text using first-order-logic.  

## First-order-logic using Prover9  
For this project I use the Prover9 software package.  
Please see: https://www.cs.unm.edu/~mccune/mace4/  
W. McCune, "Prover9 and Mace4", http://www.cs.unm.edu/~mccune/Prover9, 2005-2010.  

## DATA  
The corpus of text that is used for first-order-logic support is described in the data.txt file. This includes support on the stories of MacBeth and LadyMacBeth, Linda and Dick, and Adam and Eve.  

## LOGICAL STATEMENT TO PROVE  
Given a foolish noble and a domineering lady, and that the noble is married to the lady, show that the lady may persuade the noble to want to be king.  

## COMPILING, INSTALLATION AND RUNNING  
First, I convert the corpus of text and the logical statement to prove to first order logic in the required format for the Prover9 solver. This can be seen in the prover9_macbeth.input file.  

This input file is then run through the Prover9 software to either prove or disprove the logical statement.  

## RESULTS  
Results from the prover are found in the prover9_macbeth.output file. This shows that the logical statement is proved to be TRUE given the support from the data file.  

A more concise derivation of the proof is found in the prover9_macbeth.proof file.   

## LICENSE  
[MIT License](https://github.com/shoeloh/first-order-logic/blob/master/LICENSE)  

