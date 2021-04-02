# PyWMI-swarm-node-management-functions
PY WMI manage deployment of Java nodes across multiple servers. Windows, WMI, Python, handle process spawning and terminating, search for processes by memory properties. 

Functions written to be implemented inside a series of nested loops designed to run constantly, deploy AGI system swarm nodes in java containers across servers. The functions enable 
monitoring and tracking of the nodes at a high level without inspection of internal node activity or communication between nodes at a societal/behavioural level within their virtual environment.

The deployment system may be integrated with log data output by individual nodes in high level "executive function" learning. It also enables logging of node states, numbers, frequency of deployment/node self 
termination triggered by internal node states (local node processes) and virtual environment triggered node termination. 

Any usage is likely to vary dramatically, an example of a working system that makes use of the raw functions is provided:

Pseudo code of the deployment system:

<pyWMI functions>

<Setting periodic timers>

<Read in prepared nodes>

<Read current state of nodes across defined servers>

<Reading in external data to modify launch processes including log data outputted by nodes>

    <Conditional procedure pass based on current state * state of prepared * periodic timers * external data variables>
  
    <Reading in external data to modify launch processes>
  
    <Read data assigned to each node through its command line parameters sent to the node>
  
    <Pass conditional checks and read global variables, enter launch cycle>
  
        <Locate server with capacity for additional node>
    
        <Deploy node to server and write to logs with UID + timestamps>
    
    <On conditions and periodic timer states enter additional processes>
    
        <Read WMI information on nodes>
        
            <Perform operations on nodes dependent on WMI information + globals + periodic timers + command line parameters>
            
<Periodic timer sleeps and continue loop>

<Write log information on nodes for data analysis and learning>




