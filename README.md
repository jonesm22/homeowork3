homeowork3
==========

disclaimer: most of my times did not improve. I did notice that making a random number in some of the problems was causing
trouble, but I am not sure how to fix it. I think that I do not exactly understand how to improve efficiency but converting 
to cython.

problem number one: 

python times: about 216 microseconds 
cython times: about 216 microseconds as well

no improvement. It appears to be from my while loop.

problem number two:

python times: 6.11 microseconds 
cython times: 6.22 microseconds 

no improvement. It appears to be because of my range, sum and return

problem number three:

python times: 188 microseconds 
cython times: 187 microseconds

no improvement probably due to the return and the s=range...

problem number four:

python times: 811 microseconds
cython times: 817 microseconds

a slow down from python to cython. mainly because of my round and append as well as my numpy

problem number five:

python times: 772 microseconds
cython times: 780 microseconds 

its appears there was no improvement because of my row.append... code. I believe it is line 15. As well as the numpy 


