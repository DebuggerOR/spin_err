# spin lock error checking
experiment that tests if tiny error exits while using theoretical spin lock as peterson.

## results
when running the experiment 1000 times we got one time a counter value of 199998437 instead of 200000000.

## food for thought
check the python implementation at https://github.com/DebuggerOR/spin_err_python.  
do you think there will be error there too?  
ans - as long as there is no compilation, no problems are expected.

## see also
our slides about spin lock & contention and course material are at https://github.com/DebuggerOR/multicore_seminar.
