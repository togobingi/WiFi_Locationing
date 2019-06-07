<p align="center">
  <a href="https://ubiqum.com/programs/data-analytics-and-machine-learning-program/"><img src = "https://scontent-ber1-1.cdninstagram.com/vp/706a70a2cf2361d0b5c0c9335e9d06d1/5D6D4095/t51.2885-19/s320x320/22352400_125994984820756_7444932873942990848_n.jpg?_nc_ht=scontent-ber1-1.cdninstagram.com" width = 60></a>
</p>

<h2>Python script for indoor locationing using Wi-Fi signals</h2>

### Evaluate Techniques for Wifi Locationing

Indoor locationing: Determining a person’s physical position in a multi-building indoor space using wifi fingerprinting. 
I used this Data Set for training and evaluation: [UJIIndoorLoc Data Set](http://archive.ics.uci.edu/ml/datasets/UJIIndoorLoc)
</p><br></p>

### Data Set Summary
* Number of observations: 21,048
* Number of features: 529
* Dataset creation date: 2013
* Number of Users: 20 

### Data Set Information:

Many real world applications need to know the localization of a user in the world to provide their services. Therefore, automatic user localization has been a hot research topic in the last years. Automatic user localization consists of estimating the position of the user (latitude, longitude and altitude) by using an electronic device, usually a mobile phone. Outdoor localization problem can be solved very accurately thanks to the inclusion of GPS sensors into the mobile devices. However, indoor localization is still an open problem mainly due to the loss of GPS signal in indoor environments. Although, there are some indoor positioning technologies and methodologies, this database is focused on WLAN fingerprint-based ones (also know as WiFi Fingerprinting). 

Although there are many papers in the literature trying to solve the indoor localization problem using a WLAN fingerprint-based method, there still exists one important drawback in this field which is the lack of a common database for comparison purposes. So, UJIIndoorLoc database is presented to overcome this gap. We expect that the proposed database will become the reference database to compare different indoor localization methodologies based on WiFi fingerprinting. 

### Some Machine Learning Models Adopted
* Random Forest
* Neural Networks
* KNN 
* SVM 

### Visualization of UserID by Building & Floor Using Coordinates

![Building Wi-Fi Visualization](building_wifi_visualization.png)

<br>

### Predicted and Actual Longitude and Latitude Coordinates
![Predicted and Actual Coordinates](KNN_Pred_Real.png)
