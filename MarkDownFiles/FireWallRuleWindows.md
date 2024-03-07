# Setting Up a Firewall Rule to allow ArcGIS Server to Acess Certain Ports to Control Traffic to and from a VM Instance on Windows Machine.

### Step 1
There is a firewall built into the Windows machine itslef already, so you need to configure it to allow TCP 6443 and 6080 to allow the machine to pass through from an outside network.
This is a permanent setting in windows that needs to be completed once per virtual machine.
The first step is to log into your remote desktop on the running Windows Server, then in the start menu of the server type in "firewall" and select 
"Window Defender Firewall with Advanced Security" option. 

### Step 2
Then click on the "Inbound Rules" and select "New Rule" from dropdown, if this is not visable click on the advanced options to get acess to the full list of settings.
The select "Port" a the rule type, this will let you set what ports will be permited to pass through the firewall from the public side.

### Step 3 
The select "TCP" and enter the ports you wish to permit your firewall when acess ArcGIS Server, for example 6443 and 6080 as administration. Then click NEXT.
Leave the deault of "Allow the connection"  selected, and click NEXT.

The rule will apply for all options: Domain, Provate and Public. Click NEXT. 
Give your rule an appropriate name and description.  

This firewall rule will go love immetiatly after creation and will persit after restarts of the server. Therefore, this rull doe snot ned to be changed again.
