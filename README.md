# Our Issues
[ourissu.es](http://ourissu.es) is an open source initiative to visualize the concerns people have across the world. We'll begin our effort to make an impact in NYC. People can utilize this tool to represent their area and the issues that affect them on a daily basis. Then community leaders can analyze issues and see what their impact is.

I will begin work on this project at penapps (fall 2015) 

This is a [Google App Engine](https://cloud.google.com/appengine/docs) application. It's divides into a distinct [frontend](https://github.com/Parth-Mehrotra/ourissu.es/tree/master/frontend) and [backend](https://github.com/Parth-Mehrotra/ourissu.es/tree/master/backend). The [frontend](https://github.com/Parth-Mehrotra/ourissu.es/tree/master/frontend) is responsible for visualizing the data, and helping users submit their issues. The [backend](https://github.com/Parth-Mehrotra/ourissu.es/tree/master/backend) is responsible storing the data, and providing it back to the [frontend](https://github.com/Parth-Mehrotra/ourissu.es/tree/master/frontend) in the JSON format. The [frontend](https://github.com/Parth-Mehrotra/ourissu.es/tree/master/frontend) utilizes [Leaflet](http://leafletjs.com/), an interactive mapping library.

# Philosophy  

Currently there isn't an effective way for communities to interact with their community leaders. [ourissu.es](http://ourissu.es) aims to solve that problem with a few guiding principals.

* Everyone should feel like they're making a meaningful contribution to this "issuebase"
* It should be easy for people find issues they're passionate about
* It should be easy and rewarding for people to share issues and encourage community participation
* It should be easy for community leaders to interact with their community
* It should be easy to capture the improvement in communities

# To Download
```
git clone --recursive git@github.com:Parth-Mehrotra/ourissu.es.git
```

# To Setup Google App Engine
The following script should download and install google app engine. If this doesn't work download and follow the instructions [here](https://cloud.google.com/appengine/downloads?hl=en_US&&_ga=1.190362920.2039674957.1437930683#Google_App_Engine_SDK_for_Python)
```
sh Tools/InstallScripts/install-google-app-engine.sh
```

# To Run
```
sh Tools/Utils/google-app-engine-local-python.sh 
```
