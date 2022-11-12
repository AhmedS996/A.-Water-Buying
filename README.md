# A.-Water-Buying
explain how to solve this problem in codeforces website 

----------------------------------------------------
1. what the problem need to solve?
  #how to find algorithm to know the minimum costs that we can find
  
2. how to solve it?
  #so if cost a < b and b/a grater than 2 so that's mean the number b more than double of number one 
  so the a will be more helpful in that way.
  
  ex: if he need 10 liters and cost of a =2 and b =5
  # a < b ;
  # (b / a ) > 2
  so we will use all a 
  so if 2 x 10 = 20 -- and b x 5 = 25
  so the answer will be 20 because we use all the a, it costs less than b 
  
  #else than that we will use spicific algorithm
  so n /2 to find the liters that we will use for b 
  then b* n/2 to find the costs of b 
  2 * n/2 to find how many liters we used 
  then n-= the liters that we used in b 
  the liters that still in n we use it for a 
  
  and that's it 
  
  ex: if he need 11 liters and cost of a = 4 and b =2
  n/ 2 = 5.5 but he is long int so it will become "5" 
  b * 5 = 10<-->  the costs of b 
  2 * 5 = 10<-->  the liters of b
  n - 10 liters that we used in b 
  n it will be = 1
  so a * n = 4 
  
  the costs 4 + 10 = 14;
  
  
