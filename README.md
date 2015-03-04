# Documentation
What are test1 and test 2 blocks?

   The purpose of building these blocks is to demonstrate how work function is called in gnuradio and how it allocates memory for input and output items.

Working of the blocks:
   TEST 1:
   This Block initializes a class attribute temp with value 0 in init method.
   This value is incremented with every call to work method.
   The work method reproduces value from input and passes it as output.


   TEST 2:
   This block works similiar to Test1 with a minor exception that delay is added so that it gives us enough time to watch all the processing.


What these block Demonstrates?
   These blocks demonstrate the following issues with gnuradio:
     1. Reason why values from slider do not reflect quickly in gnuradio.
     2. One may not be able to efficiently access external resources through gnuradio unless the problem is solved.

Problem Statement:
   The block test1 executes prematurely without waiting for the next block to complete its operation.
