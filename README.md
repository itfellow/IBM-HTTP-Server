# Dummy guide to install no-charge IBM-HTTP-Server
IBM-HTTP-Server installation

by default IBM HTTP server come together with IBM websphere application server .
if you require only IBM HTTP server , just try following steps.


## https://www-01.ibm.com/support/docview.wss?uid=swg21972167

Option 2: Install using IBM Installation Manager

Download IBM Installation manager ( require IBM ID to proceed)
--------------------
refresh pack: 1.8.9.4-IBMIM-WIN64-20190423_2015

IBM Installation Manager Install Kit for all x86_64 Windows versions supported by version 1.8.9.4

The following files implement this fix.

agent.installer.win32.win32.x86_64_1.8.9004.20190423_2015.zip (166.15 MB)
-----------------

install IBM Installation manager
copy the url for software require i.e. IBM HTTP Server version 8.5
add to repository http://www.ibm.com/software/repositorymanager/com.ibm.websphere.IHSILAN.v85
install done.
set the port number if require.

