# Securing your Data using ArcGIS Pro Online Views
## You can make certain fields in a layer visible and others hidden, even through the rest end point 

### Step 1
Go to item detail page of hosted feature layer on AGOL, click on the tab "Create View Layer" to open up option list. In the options drop down click on "View Layer".
Once inside the "Create View Layer" you need to select the layer you want to manage if not already selected. Now click "NEXT" and go to step 2 "Define View".

### Step 2
The next step is adding a filter expression to the layer, there you can select different filter options with the data from the layer such as the attributes. Once an expression is created you can
see on the map what the filter is generating. 

### Step 3
Next you can add an "Area of Interest", this can be generated using a draw tool to select a certain area that you want your filter to affetc. If no area of interest is selected, the entire layer 
will have the filter applied to it. 

### Step 4
The next option you have is in the "Fields" option tab, here you can press on the "X" beside the attribute names and remove the fields you no not want public.THIS DOES NOT DELETE THEM.
Once this step is complete, go back to the begining and select "Next" to go onto step 3 "Create View". 

### Step 5
Now you can create view, this is not a copy of the original data but modifying the orginal. This happens at a data level, meaning you cannot acess what you filtered out data even through the
Rest End Point.
Therefore, in the end you will have two feature layers of the orginal feature layer. One is untouched and the other has the filter applied to it, if you apply the view feature layer to a map you will only 
see the data allowed to display but you will still privatly have all the data on the orginal feature layer.

### EXTRA 
If you make a mistake or want to change the filter added to the view feature layer you just go into the iteam details page of the view feature later. Inside its items page go to the "Settings" top tab. 
Inside the settings there is a "Update View", in there you can edit the filter and then click on "Update". 
*** AGAIN this is not a duplicate ***
