# PredUrTick
Car parking ticket prediction for the city of New York.<br><br>
<h1>All Dataset Files </h1>
Link:https://drive.google.com/open?id=1iOYIlAlMoQAyVy0fQGf-4TeJ_4utU4s6 <br>
Youtube Link to presentation: https://youtu.be/zvAsq2L9cuQ

<h1>Files Information </h1>

<h4>1. To Run Application GUI:</h4>
<b>File:</b> Final Gui Model Implementation.ipynb<br>
<b>Data:</b> Dataset/ParkingData_Month_Time_Week.csv<br><br>

<h4>2. EDA Files:</h4>
<b>Folder:</b> EDA + Data Preprocessing/<br><br>
<b>Files:</b> <br>
      1. EDA-1.ipynb<br>
      2. EDA-2.ipynb<br>
      <b>Data:</b> Dataset/Sample_data_2017.csv<br><br>

<h4>3. Data Visualization:</h4>
<b>Folder:</b> EDA + Data Preprocessing/<br><br>
<b>Files:</b> <br>
      1. <b>Location based heat maps.ipynb</b><br>
         Heatmaps plotted for precinct-based and street-based analysis on the map<br>
      2. <b>Time based heat maps.ipynb</b><br>
         The time and date is divided over hours, daily, week and monthly data. <br>
         Heatmap with respect to time plotted for hourly, daily, weekly, monthly.<br>
         The heatmaps are quite interactive and they show variation over time. <br>
          
<b>Data:</b> Dataset/Sample_NaStreet_Removed.csv<br>
<b>Folder:</b> Maps<br>
Has all the maps generated during data visualization<br>
<p><u><b>Note:</b></u> Internet Connection is necessary for the maps to work</p><br>

<h4>4. Data Pre-Processing:</h4>
<b>Folder:</b> EDA + Data Preprocessing<br><br>
<b>Files:</b><br>
      1. <b>Get Coordinates.ipynb - to get latitude, longitude from street name using google geoAPI</b><br>
         <b>Data:</b> Dataset/Sample_data_2017.csv<br><br>
      2. <b>Time based dataset.ipynb - to add time slot column to the data</b><br>
         <b>Data:</b> Dataset/Sample_data_2017.csv<br><br>
      3. <b>Get data based on bounding box.ipynb - to get data only belonging to the state of New York</b><br>
         <b>Data:</b> Dataset/Sample_NaStreet_Removed.csv<br><br>
      4. <b>Parking Ticket Dataset.ipynb - to make month and days into numbers and prepare final dataset for model implementation</b><br>
         <b>Data:</b> Dataset/bounded box data.csv<br><br>
         
<h4>5. Performance Metrics:</h4>
<b>File:</b> Performance Metrics for all cases<br>
<b>Data:</b> Dataset/ParkingData_Month_Time_Week.csv<br>

<h4>6. Kmeans:</h4>
<b>Folder:</b> K means/models<br>
<b>File:</b> K means/K Means clustering to predict prone areas.ipynb<br>
<b>Dataset:</b> Dataset/ParkingData_Clustered_Kmeans.csv<br>
<u><b>Note:</b></u> The code for generating weights has been commented out. Download the models and dataset to make predictions.<br>

        









