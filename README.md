# spin_err
experiment that tests if tiny error exits while using theoretical spin lock as peterson.

## result
when running the experiment 1000 times we got a counter value of 199998437 instead of 200000000.

## foof for thought
check the python implementation at https://github.com/DebuggerOR/spin_err_python.
do you think there will be error there too?
ans - as long as there is no compilation, no problems are expected.