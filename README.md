Timmer
======

A generic Timmer class in C/C++. Feasible for profiling. Compatible with both Windows and Mac. Tested on Window 7 and Mac OS Mavericks and Linux 12.04. 


Usage
======

Sample Code:

    Timmer::begin( "Function A" ); 
    // Do sth
    Timmer::end( "Function A" ); 
    cout << Timmer::summery() << endl; 

Out put will be:

    +--------------------
    | Profiling Summery ...
    +---------------------------------------
    | Function Name          |     Total Time |   Be Called |        Average |
    | Function A             |     7.80381 ms |     1 times |     7.80381 ms |
    
  
