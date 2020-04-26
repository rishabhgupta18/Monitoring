# Multithreaded Time based Monitoring System

<p>Monitoring system can be used when there is a need to execute a process on a specific interval of time. Monitoring class accepts the Predicate<Integer> upon match, it executes the process.<br/> 
  Monitoring has a Timer class which increments every second and verify the Predicate.</p>


<ul>To use Monitotring - 
<li>Extend the class and provide the Predicate in the constructor</li>
<li>Override the <b>operation</b> method and add the steps which need to be executed when the predicate matches</li>
  <li>[Optional] Override the close method<b>(super.close is required to close the monitor timer)</b>in case any additional resource needs to be closed.</li> 
</ul>
