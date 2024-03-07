# Setting Up a Firewall Rule to allow ArcGIS Server to Acess Certain Ports to Control Traffic to and from a VM Instance on Google Cloud.

### Step 1
Once logged into your Google Cloud account go to the hamburger symbol on the left of the screen and select Compute Engine and then VM Instances, this is where you can start your VM to acess your ArcGIS Server.

### Step 2
Once in the page for VM Instances, go to the Related Actions and sect the "Set up firewall rules" tab. Then at the top of this new page, click on the "Create Firewall Rule" tab. 

### Step 3 
Once you get into the fillable page, enter as follows:
Name: flemingrdp44
Logs: off
Network: default
Priority: 1000
Direction: Ingress
Action on match: Allow
Targets: All instances in the network
Source filter: 1Pv4 range
IP Range: (enter your computers external IP or 0.0.0.0/0 for every IP/location)
Second source filter: None
Ports: 444, 6443, 6080
Enforement: Enabled 
Insights: None

Then click "Create"


