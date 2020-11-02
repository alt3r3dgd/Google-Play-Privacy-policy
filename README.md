# What is your data taken for

### Tap, 10 and another POINTLESS game
The apps use Google Mobile Ads SDK for Unity to display ads. This SDK collects users' other apps usage data, age, gender etc. Not your name or password, obviously. The Google Mobile Ads SDK is a Google Play sertificied ad network (since it's Google's) and it can't use your data in wrong ways.

### Pop
Since I started making games in Godot, I have to use other libraries for ads.  
To implement ads in my game I used [Shin-NiL/Godot-Android-Admob-Plugin](https://github.com/Shin-NiL/Godot-Android-Admob-Plugin).  
To implement Google Play Games functionality I used [cgisca/PGSGP](https://github.com/cgisca/PGSGP).  
Only those two modules can collect data from players, the rest of the game **doesn't**.
