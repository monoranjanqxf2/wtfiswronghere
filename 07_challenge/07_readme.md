a.logical error. 99 should be printed but it didn't
b.range function always end at n-1 value if you are passing n. so for n you have to pass n+1.
    In this case inside the for loop 1,max_num is passed. so the loop will be run from 1 to max_num-1.
    In order to include max_num we have to pass max_num+1.
c.in range function in order to include the number you have to increase the no by 1.