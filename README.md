# Multithread Time based Monitoring System

<p>Monitoring can be used where there is a need to execute a process on a specific interval of time. Monitoring class accepts the Predicate<Integer>, Upon match it executes the operation.
  Monitoring has a Timer class which increments every second and verify the Predicate.</p>


<ul>To use Monitotring - 
<li>Extend the class and provide the Predicate in the constructor</li>
<li>Override the <b>operation</b> method and add the steps which need to be executed when the predicates matches</li>
<li>[Optional] Override the close method(super.close is required to close the monitor timer)in case any additional resource needs to be closed.</li> 
</ul>
