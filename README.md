### This is a Ionic tutorial example made for http://www.gajotres.net/using-google-maps-with-ionic-framework

Follow these instruction to deploy this example:

1. git clone https://github.com/Gajotres/IonicGoogleMapsExample.git
2. cd IonicGoogleMapsExample
3. ionic platform add android
4. cordova plugin add cordova-plugin-whitelist
5. Find AndroidManifest.xml and add these lines:
    &lt;uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" /&gt;
    &lt;uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" /&gt;
    &lt;uses-permission android:name="android.permission.ACCESS_LOCATION_EXTRA_COMMANDS" /&gt;
5. npm install
6. ionic serve -> To see if everything is working as it should
7. ionic run android -l -c -s6