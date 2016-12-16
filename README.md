## Caesium Command Line Tools
##### CCLT - v0.9.1-beta (build 20160808) - Copyright &copy; Matteo Paonessa, 2016. All Rights Reserved.

----------

###### REQUIREMENTS
* [mozjpeg](https://github.com/mozilla/mozjpeg)
* [zopflipng](https://github.com/google/zopfli)
* [lodepng](https://github.com/lvandeve/lodepng)

----------

###### TESTED PLATFORMS
* Mac OS X El Capitan (v10.11.4)
* Arch Linux

----------

###### INSTALLATION
See INSTALL for more details.

----------

###### USAGE EXAMPLES

Losslessly compress ```image1.jpg```, located in the ```home``` directory, into a folder called ```output```
```
$ caesiumclt -q 0 -o ~/output/ ~/image.jpg
```

Compress ```image1.jpg```, located in the ```home``` directory, into a folder called ```output``` with lossy compression and quality set to 80
```
$ caesiumclt -q 80 -o ~/output/ ~/image.jpg
```

Losslessly compress ```image1.jpg```, located in the ```home``` directory, into a folder called ```output``` and keeps EXIF metadata
```
$ caesiumclt -q 0 -e -o ~/output/ ~/image.jpg
```

Losslessly compress ```Pictures``` folder and subfolders, located in the ```home``` directory, into a folder called ```output```
```
$ caesiumclt -q 0 -R -o ~/output/ ~/Pictures
```

----------

###### TODO
* Code cleaning
* Keep folder structure

----------

###### KNOWN ISSUES
* It does not work on Windows unless you port getopt to it

----------

###### CHANGELOG
* 0.10.0-beta - Switched to cmake and libcaesium
* 0.9.1-beta - Initial development stage

Check the [Commits](https://github.com/Lymphatus/CaesiumCLT/commits/master) for a detailed list of changes.

----------

###### RESOURCES
* CaesiumCLT website - [http://saerasoft.com/caesium/clt](http://saerasoft.com/caesium/clt)
* Caesium website - [http://saerasoft.com/caesium](http://saerasoft.com/caesium)
* CaesiumCLT Git Repository - [https://github.com/Lymphatus/CaesiumCLT](https://github.com/Lymphatus/CaesiumCLT)
* Author website - SaeraSoft - [http://saerasoft.com](http://saerasoft.com)
* Twitter - [Matteo Paonessa](https://twitter.com/MatteoPaonessa)
