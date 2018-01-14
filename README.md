# haskell-notation-meaning  

| Notation | Meaning | Example |    
| :--- | :------- | :--------- |  
| [ ] | List | [1,2] |  
| <- | Draw element from list | [x \| x <- [1, 2]] |  
| [ \| ] | List comprehension | [x \| x <- [1, 2]] |  
| ( ) | Tuple | (1, True) |  
| :: | Show the type | 5 :: Integer | 
| => | Left part of => is typeclass constraints and right part is actual type | Num a => (a, Bool) |  
| $ | Application operator. $ has low, right-associative binding precedence, so it sometimes allows parentheses to be omitted; | main = print $ sqrt $ 2 + 3 |  
