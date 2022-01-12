### About
Some useful command from openshift


* List everything from node
    * oc get all
    * oc get services
    * oc get service <name> -o yaml
      * e.g oc get service todo -o yaml
* Project Name or switch project
  * oc project 


###Build Configs
* List 
  * oc get buildconfigs
* Creating a buildoncifg
  * TODO
* Delete a buildconfig
  * oc delete buildconfig <name from the list>

### Templates
* List 
  * oc new-app -L