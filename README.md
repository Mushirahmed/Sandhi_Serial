# Documentation
What are test1 and test 2 blocks?<br>

   The purpose of building these blocks is to demonstrate how work function is called in gnuradio and how it allocates memory for input and output items.
<br><br><br>
Working of the blocks:<br>
   TEST 1:<br>
   This Block initializes a class attribute temp with value 0 in init method.<br>
   This value is incremented with every call to work method.<br>
   The work method reproduces value from input and passes it as output.<br>


   TEST 2:<br>
   This block works similiar to Test1 with a minor exception that delay is added so that it gives us enough time to watch all the processing.<br><br><br>


What these block Demonstrates?<br>
   These blocks demonstrate the following issues with gnuradio:<br>
     1. Reason why values from slider do not reflect quickly in gnuradio.<br>
     2. One may not be able to efficiently access external resources through gnuradio unless the problem is solved.<br>

Problem Statement:
   The block test1 executes prematurely without waiting for the next block to complete its operation.
