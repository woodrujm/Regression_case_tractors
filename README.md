The Regression Case Study was the first case study we did at Galvanize. 
It was scheduled for the first day of the fourth week of the course. 
Our prior material armed us with few supervised learning techniques.
In particular, the sole weapon in our arsenal was Logistic Regression.
The goal of the case study was to predict the sale price of a particular piece of heavy equipment at auction based on a number of variables. 
The data was sourced from auction result postings and includes columns on each of the following:
[SaleID, MachineID, ModelID, datasource, auctioneerID, YearMade, MachineHoursCurrentMeter, UsageBand, Saleprice, fiModelDesc, fiBaseModel, fiSecondaryDesc, ProductSize, ProductClassDesc, State, ProductGroup, ProductGroupDesc, Drive_System, Enclosure, Forks, Pad_Type, Ride_Control, Stick, Transmission, Turbocharged, Blade_Extension, Blade_Width, Enclosure_Type, Engine_Horsepower, Hydraulics, Pushblock, Ripper, Scarifier, Tip_control, Tire_size, Coupler, Coupler_System, Grouser_Tracks, Hydraulics_Flow, Track_Type, Undercarriage_Pad_Width, Stick_Length, Thumb, Pattern_Changer, Grouser_Type, Backhoe_Mounting, Blade_Type, Travel_Controls, Differential_Type, and Steering Controls]

As you can imagine, there was a fair amount of sparsity in the data columns. 
This was most likely due to the fact that not all of these features are relevant to every piece of equipment (think blade width and backhoe).
However, this characteristic presented it's self as a path to the most significant learning experience.

Overall, the most important lesson was time management. 
This data set provided us with many opportunities to get "caught up in the weeds." 
Inevitably, as new learners tend to do, we wanted to perfect every minor detail.
Five hours into our eight hour project we didn't even have a working model, we had spent the entire time doing EDA and feature engineering. 
In retrospect, some kind of dimensionality reduction may have been incredibly useful. 
Absent of throwing out columns purely based on "fullness" I'd like to try a clustering algorithm to increase the f1 score.
A basic Random Forest ended up having significant predictive power on the data. 
However, the fact that we only knew Logistic Regression ended up being a blessing in disguise.
Feature engineering played an important role in the modeling process, something that I imagine will remain extremely useful in my future as a data scientist.
