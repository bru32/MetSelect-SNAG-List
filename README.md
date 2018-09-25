# MetSelect-SNAG-List
SNAG list issues 

# #1 (25/09/2018) - N du Plessis

## **_Condenser Selection Issue_**

Stating that a condenser is required with 69.2kW of THR, the tool selected a single coil with less capacity than the required capacity.
It also did not incorporate the altitude correction factor of the capacity, as the correction factor would be 74.47kW @ sea level.

![alt text](UndersizedCondenser.JPG "Undersized Condenser Selection")

It also only gave one option to choose from.
If possible, we would like at least 3 options to select from, thus giving the person selecting a choice, thus preventing just having one choice that may be incorrect.

![alt text](RecSelector.JPG "Condenser Selection Preview")

How our current condenser selection tool works is as followed:
 First you select the area you need the condenser to operate in.
 The software can then automatically state the altitude of the selected area (not displayed here but calculated automatically in the background)
 Or you can overwrite this value with your own value, by selecting manual input @ the system altitude **drop down box**.
 Then the THR capacity is entered into the edit box next to the THR **drop down box**.
 Below it, the corrected THR value is displayed for selection purposes, as this is not an automated selection program, it still relies on the user to make the selection.
 In the top-middle of the image, there are 4 different sectors, **1** being the *Evaporatoring Temperature*, **2** being the *Condensing Temperature*, **3** being the *Refrigerant* and **4** being the *Ambient*, as this is also not an automated process.
 Below this section, the user can select the condenser type.
 Below this is the results from all the condenser at the given conditions.
 
 THe ones marked in **RED** are not a suitable match
 
 THe ones marked in **YELLOW** are within 5% (up or down) of the required value
 
 THe ones marked in **GREEN** are a suitable match
