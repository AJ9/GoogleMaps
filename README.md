# GoogleMaps


A basic XCode project including a working google maps demo.

The full Google Maps walkthrough can be found [here](https://developers.google.com/maps/documentation/ios/start), but for a quick start download this project and add your Google Maps API key see [Usage](https://github.com/AJ9/GoogleMaps#usage). 

# How to get a Google Maps API Key

Google provides a simple [guide](https://developers.google.com/maps/documentation/ios/start#obtaining_an_api_key) to do this, but here is a more graphical version:

1. Head over to this [link](https://code.google.com/apis/console/?noredirect). It will take you to the Google APIs Console.
If you've not signed into a Google account for the browser, go ahead and sign in or sign up. 

2. If you've used the Google APIs Console before you will be taken to your last project, it will look something like this.
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/Previous%20Sign%20In.png "Previously used Google APIs Console")
If you've never used the Google APIs Console before you'll see a screen like this. 
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/First%20Time.png "First Time")
Click *Create Project* to continue. This will create a default project called *API Project*. Not a particularly helpful name, so follow the steps below. 
3. Create a new project by clicking the current project name (*API Project* for example) and under *Other Projects* choose *Create...* and include a suitable name. 
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/Create%20Project.png "Create Button")
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/Suitable%20Name.png "Suitable Name")
4. This should take you to the *Services* area, if not select this from the left panel and scroll to enable *Google Maps SDK for iOS*
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/Choose%20Maps%20API.png "Choose Maps API")
5. Once enabled choose *API Access* from the left panel
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/API%20Access.png "API Access")
6. This will bring up a view to all the API keys for this particular project. Select *Create new iOS key..* 
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/iOS%20Key.png "iOS Key")
7. From here you can enter your bundle ID (*com.example.yourprojectname* for example) or leave it blank for any application. 
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/Bundle%20ID.png "Bundle ID")
8. Copy your API key and you're done!
![alt text](https://raw.githubusercontent.com/AJ9/GoogleMaps/master/Walkthrough/Key.png "API Key")



# Usage

You need to add your own Google Maps API Key to this project! This is done changing this line in the **AppDelegate.m** to include your Google Maps iOS key.

`NSString * GoogleMapsAPIKey = @"YOUR-KEY";`

An example might look like: 


`NSString * GoogleMapsAPIKey = @"BGzaSyAbfNKVd_EWpC-f2TjGBoCX17tc6PQm4-k";`


# Licence

**Bottom Line - Use however you like**

The MIT License (MIT)

Copyright (c) 2014 Adam Gask

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
