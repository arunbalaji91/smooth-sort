# smooth-sort
## STEPS: 1. insert  2. dequeue

## INSERT:
  ## 1.1  if LN(k) + LN(k+1) = LN(k+2)
        #### reheap (k, k+2)
  #### 2.1  else 
          #### if k == 1
              #### new num's k = 0
          #### else
              #### new num's k = 1
  #### 3.0  sort the roots

## DEQUEUE:
  #### loops
    #### if did sort the roots
        #### reheap
  
  
  
