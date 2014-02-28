sml-code
========

assignments
val date1 = (12, 11, 2011)
val date2 = (11, 11, 2011)
fun is_older(d1: int*int*int, d2: int*int*int) = 
   if #1 d1 < #1 d2 orelse #2 d1 < #2 d2 orelse #3 d1 < #3 d2
   then
        0
    else
        1
is_older(date1 , date2);
