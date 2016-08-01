# Cordova-Admob-simplecode
Cordova/Phonegap AdMob Plugin

The FASTEST and EASIEST TO USE Cordova Admob plugin for Android, iOS and Windows phone. We do not send your apps details to our servers. Pure OpenSource Admob code. Allows preloading and automatic loading of interstitials and banners plus more. Works with Cordova, Phonegap, Intel XDK/Crosswalk, Ionic, Meteor and more.
the plugin => cordova-plugin-admob.zip
Create your app
cordova create hallo com.example.hallo HalloWorld

cd hallo

cordova platform add android
Add the plugin
cordova plugin add cordova-plugin-admob-simple
OR

cordova plugin add https://github.com/sunnycupertino/cordova-plugin-admob-simple

in file index.html
change the key
banner and  interstitial
	ios : {
					banner: 'ca-app-pub-6869992474017983/4806197152',
					interstitial: 'ca-app-pub-6869992474017983/7563979554'
				},
				android : {
					banner: 'ca-app-pub-5051980663688704/6989554279',
					interstitial: 'ca-app-pub-5051980663688704/5512821071'
				},
				wp8 : {
					banner: 'ca-app-pub-6869992474017983/8878394753',
					interstitial: 'ca-app-pub-6869992474017983/1355127956'
				}
