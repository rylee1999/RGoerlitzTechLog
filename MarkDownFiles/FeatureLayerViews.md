# Securing your Data using ArcGIS Pro Online Views
## You can make certain fields in a layer visible and others hidden, even through the rest end point 

### Step 1
Go to item detail page of hosted feature layer on AGOL, click on the tab "Create View Layer" to open up option list. In the options drop down click on "View Layer".
![image](https://github.com/rylee1999/RGoerlitzTechLog/assets/146375958/46ce9c63-a07f-43ba-b00d-d14f2c20b37f)





Once inside the "Create View Layer" you need to select the layer you want to manage if not already selected. Now click "NEXT" and go to step 2 "Define View".
![image](https://github.com/rylee1999/RGoerlitzTechLog/assets/146375958/32dbc042-7407-44df-bf36-ed2c3be49774)


### Step 2
The next step is adding a filter expression to the layer, there you can select different filter options with the data from the layer such as the attributes. Once an expression is created you can
see on the map what the filter is generating. To get into these options in step 2, lcik again on the layer you want to modify.

### Step 3
Next you can add an "Area of Interest", this can be generated using a draw tool to select a certain area that you want your filter to affetc. If no area of interest is selected, the entire layer 
will have the filter applied to it. 

### Step 4
The next option you have is in the "Fields" option tab, here you can press on the "X" beside the attribute names and remove the fields you no not want public.THIS DOES NOT DELETE THEM.
Once this step is complete, go back to the begining and select "Next" to go onto step 3 "Create View". 
![image](https://github.com/rylee1999/RGoerlitzTechLog/assets/146375958/4113d6de-1917-4640-806c-70260e859b4c)



### Step 5
Now you can create view, this is not a copy of the original data but modifying the orginal. This happens at a data level, meaning you cannot acess what you filtered out data even through the
Rest End Point.
Therefore, in the end you will have two feature layers of the orginal feature layer. One is untouched and the other has the filter applied to it, if you apply the view feature layer to a map you will only see the data allowed to display but you will still privatly have all the data on the orginal feature layer.
![image](https://github.com/rylee1999/RGoerlitzTechLog/assets/146375958/d8676758-cf2c-4027-8c26-0057c0602008)

## View feature layer rest end point, showing only the selected fields
![image](https://github.com/rylee1999/RGoerlitzTechLog/assets/146375958/47e9262c-29ab-4b02-948d-129e0e43a054)




## Orginal feature layer rest end point, showing all feilds
![image](https://github.com/rylee1999/RGoerlitzTechLog/assets/146375958/b30451ae-c5f9-4140-ac7e-60b814215762)




### EXTRA 
If you make a mistake or want to change the filter added to the view feature layer you just go into the iteam details page of the view feature later. Inside its items page go to the "Settings" top tab. 
Inside the settings there is a "Update View", in there you can edit the filter and then click on "Update". 
*** AGAIN this is not a duplicate ***
![image](https://github.com/rylee1999/RGoerlitzTechLog/assets/146375958/9c8c04dd-b03c-4878-bcb6-84fafa921608)

