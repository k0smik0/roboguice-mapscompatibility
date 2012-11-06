# This is a fork of Roboguice

Here we have maps support compatibility, using [this][2] android-compatibility-support fork.  
("This" is 9re's version, forked by petedoyle's one, with some my contributions).

In "libs" directory you can find "android-support-v4-r9-googlemaps-core.jar" and "android-support-v4-r9-googlemaps-maps.jar":  
they are needed in order to right compile this roboguice fork.  

Roboguice library is splitted in 2 jars, "core" and "maps":

- "core" provides all except RoboFragmentMapActivity, RoboMapActivity and RoboMapFragment  
- "maps" provides those 3 files
  
  
  
      

[see roboguice](http://code.google.com/p/roboguice/)

[2]: https://github.com/9re/android-support-v4-googlemaps