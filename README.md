# Le-Monde-puzzle-1146

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

The Puzzle
==========



Everyday of the month, take 0, 1 or 2 units. If one unit taken past day, next day none can be taken. If two units taken two day ago, none can be taken the current day. What is the strategy maximising the number of units  for February? March? April? Generalise to 0,..,3 units taken each day with 0 compulsory three days after taking 3 units.

as taking 2-1-0 (or 3-2-1-0) sounds like the optimal strategy. Except at the final step when 2, 2-2, 2-2-0, and 1-0-2-2 are best. But then why would one distinguish between the three months..?! Because the outcome differ, as 30, 32, and 33, resp. (or 45, 48 and 51). With an average increase of 1 in the first case and 1.5 in the second.

Another puzzle took too much of my time, namely a code golf challenge to devise a code taking as input a matrix of moves over an n x x grid and returning as input the number of nodes and transient tributaries for each loop (or irreducible set) of the moves. Which I solved by running Markov chains from each starting point long enough to reach stationarity. Entering the moves as:

n=3;M=matrix(sample(1:4,n^2,rep=T),n)

and returning the result via 390 bytes

Code of Golf Challenge : https://codegolf.stackexchange.com/questions/204694/analyze-the-flow
