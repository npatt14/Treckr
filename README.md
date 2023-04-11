# Treckr

This project was created alongside of Paul Hudsons “Build your first iOS app with SwiftUI” video. This app is called “Treckr”. 
Treckr portrays a selection of locations on a map and allows users to view said location and read up about it in detail. 

This app utilizes the MapKit and CoreLocation frameworks. The readable information about each location is stored in a JSON format. 
This JSON data is located using Bundle.main.url and the JSON data is converted to Swift type using JSONDecoder.
This process is done within the ‘Locations’ file. 
