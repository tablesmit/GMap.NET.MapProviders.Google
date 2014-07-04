GMap.NET.MapProviders.Google
============================

Google Maps API v3 Integration for GMaps (http://greatmaps.codeplex.com/)

The source code is freely available under the terms of MIT Licence. 

Source: https://github.com/IsNull/GMap.NET.MapProviders.Google

##Details
This is basically a new MapsProvider implementation using the new Google Maps API v3. 
This project depends on the [.NET Google API Wrapper](https://github.com/ericnewton76/gmaps-api-net)

##Usage

* The first thing you have to do is to obtain a Google Maps API v3 Key. You will retrive a google id and a google key.
* Put this credential information in a string formated as  
    * _id=your-google-id;key=your-google-key_
* You can now set your credentials for all Google Business Providers by setting your credential string to `GMapProvidersBusiness.GoogleCreditalString`
* Now you can use the Map-Providers in GMapProvidersBusiness like any other of GMap.NET by setting a Map-Provider to your GMap.NET Map.


