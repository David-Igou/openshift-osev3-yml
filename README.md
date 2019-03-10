Openshift's example documents recommend using a massive .ini file to store all your hosts and variables

It is much cleaner to use yaml in group_vars. Here is a basic template, feel free to use, distribute, and update. I installed Openshift 3.11.69 with this. I'm pretty sure updates to openshift-ansible broke some stuff
