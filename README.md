# flickr-image-gallery
A React Native mobile application built with Expo that displays recent images from Flickr, supports offline caching, and provides a simple drawer-based navigation UI.
Project Objective

To create a mobile app that:

Fetches recent images from the Flickr API

Displays them in a clean, scrollable grid

Caches data locally for offline usage

Refreshes only when API data changes
(Similar to Instagram feed behavior)
Features

📷 Fetches recent images from Flickr API

🗂️ Offline caching using AsyncStorage

📶 Works without internet after first load

🔄 Updates cache only when API data changes

🧭 Left drawer navigation with Home screen
Tech Stack

React Native

Expo

Axios – API calls

AsyncStorage – Local caching

React Navigation (Drawer)

Expo Go (for testing)
Offline Mode Test

Open the app with internet ON

Let images load

Close the app

Turn internet OFF

Reopen the app

✅ Previously loaded images will still appear
➡️ Confirms offline caching is working
⚡ Fast image loading (URL-based caching)

📱 Built using Expo (React Native)
