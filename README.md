# ALGORITMOGenetico2017


create inicial population P
evaluate the individuals of P
stop criteria <- epoch >=MAX_EPOH OR 
while(not reach the stop criteria)
  loop from l to N
   select two parents
   generate two children crossing the two chosen parents
    mutate the child if it is chosen to.
   insert two children into population NEW_PQP
  end loop

 P <- NEW_POP
 evaluate the individuals of P
 stop criteria <-epoch >= MAX_EPOCH OR found a good individual
end while
