import hudson.FilePath
import hudson.model.Node
import hudson.model.Slave
import jenkins.model.Jenkins
import groovy.time.*

Jenkins jenkins = Jenkins.instance
def jenkinsNodes =jenkins.nodes

    for (Node node in jenkinsNodes) 
    {
         println "'$node.nodeName' can take jobs !!!"
         print "Slave: " + node.getNodeName() + "\n";  
         print "Label: " + node.getLabelString() + "\n\n";
         println('Jobs running in the current slave: ' + node.getComputer().getTiedJobs().toString());
    }
   
