# PredUrTick
Car parking ticket prediction for the city of New York.<br><br>
<h1>All Dataset Files </h1>
Link:https://drive.google.com/open?id=1iOYIlAlMoQAyVy0fQGf-4TeJ_4utU4s6

<h1>Files Information </h1>

1. To Run Application GUI:<br>
File: Final Gui Model Implementation.ipynb<br>
Data: Dataset/ParkingData_Month_Time_Week.csv<br><br>

2. EDA Files:<br>
Folder: EDA + Data Preprocessing/<br><br>
Files: <br>
      1. EDA-1.ipynb<br>
      2. EDA-2.ipynb<br>
      Data: Dataset/Sample_data_2017.csv<br><br>

3. Data Visualization:<br>
Folder: EDA + Data Preprocessing/<br><br>
Files: <br>
      1. Location based heat maps.ipynb<br>
         Heatmaps plotted for precinct-based and street-based analysis on the map<br>
      2. Time based heat maps.ipynb<br>
         The time and date is divided over hours, daily, week and monthly data. <br>
         Heatmap with respect to time plotted for hourly, daily, weekly, monthly.<br>
         The heatmaps are quite interactive and they show variation over time. <br>
          
Data: Dataset/Sample_NaStreet_Removed.csv<br><br>
Folder: Maps<br>
Has all the maps generated during data visualization<br><br>
<p>Note: Internet Connection is necessary for the maps to work</p><br>

4. Data Pre-Processing:<br><br>
Folder: EDA + Data Preprocessing/<br><br>
Files:<br>
      1. Get Coordinates.ipynb - to get latitude, longitude from street name using google geoAPI<br>
         Data: Dataset/Sample_data_2017.csv<br><br>
      2. Time based dataset.ipynb - to add time slot column to the data<br>
         Data: Dataset/Sample_data_2017.csv<br><br>
      3. Get data based on bounding box.ipynb - to get data only belonging to the state of New York<br>
         Data: Dataset/Sample_NaStreet_Removed.csv<br><br>
      4. Parking Ticket Dataset.ipynb - to make month and days into numbers and prepare final dataset for model implementation<br>
         Data: Dataset/bounded box data.csv<br><br>
        









