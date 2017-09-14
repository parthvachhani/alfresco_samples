This project contains sample webscript to provision Read access to user on a specific node. Please note this is a quick and dirty coding(No exception handling,no loggers etc..)

/* ------ Web script takes 2 arguments ------- */
user=UserName of the user to whom access should be provided 
node=NodeRef of the node on which the access should be provided 

/* --------- Files used in the poject ----------- */

config\alfresco\extension\templates\webscripts\accesscontrol.get.desc.xml (all the .get should be replaced by .put as it is update)
config\alfresco\extension\templates\webscripts\accesscontrol.get.js
config\alfresco\extension\templates\webscripts\accesscontrol.get.json.ftl
config\alfresco\module\com.example\context\webscript-context.xml
config\alfresco\module\com.example\module-context.xml
