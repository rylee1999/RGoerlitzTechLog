# Plublishing Map Service From ArcServer to AGOL

### Step 1
Once you have publishsed your map on ArcGIS Pro, enter the server's name into your browser like this : https://[server's name]/arcgis/rest/services/[Map Name]/MapServer
This will get you the map servers rest end point 

### Step 2 
Go onto AGOL and go to "My Content" --> "new item" --> "URL" --> insert Map Server rest end point  URL --> 
Leave as is if you want a MapService Map Image or add /0 to the end of URL to make it a MapService Feature Layer

--> Add item details (description, summary, tags)
