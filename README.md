# Multithread Time based Monitoring System

Monitoring can be used where there is a need to execute a process on a specific interval of time. Monitoring class accepts the Predicate<Integer>, Upon match it executes the operation.
Monitoring has a Timer class which increments every second and verify the Predicate.
To use Monitotring - 
  Extend the class and provide the Predicate in the constructor
  Override the <b>operation method and add the steps which need to be executed when the predicates matches
  [Optional] Override the close method(super.close is required to close the monitor timer)in case any additional resource needs to be closed. 
