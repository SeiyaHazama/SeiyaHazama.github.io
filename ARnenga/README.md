# ARnenga

![https://www.w3.org/TR/html5/](https://img.shields.io/badge/HTML-5-orange.svg)

## Overview

This project is Web AR using [AR.js](https://github.com/jeromeetienne/AR.js) and [A-Frame](https://aframe.io/). This project is very simply. So, You can use as Web AR example.
To use Web AR using AR.js and A-Frame, Encrypt with SSL is needed in addition Web Server.

## Prepare 3D model and AR marker

This AR is use Greeting Card. So, this 3D model is "Kagami Mochi". Because I'm Japanese.

This 3D model is refered by [The Models Resource](https://www.models-resource.com/mobile/digimonlinkz/model/21573/). But extension on this model is ".dae". So, need convert ".dae" to ".obj" and ".mtl".  Anyway, I used [online tool of convert 3D model](http://www.greentoken.de/onlineconv/).

AR marker is can create by [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html). To improve the precision of Marker, Marker is need simple. For example, useless marker is complex character or image. Good marker is simple character. By the way, this marker in use this project is, character is "元旦", font is "Hiragino Kaku Gothic Standard" 60pt, Pattern Ratio is 7.50.

## Usage this repository

On terminal

```
git clone https://github.com/SeiyaHazama/ARnenga.git
```

* git command is needed in addition terminal.

## Motion
![](https://user-images.githubusercontent.com/31854581/47959344-e332c580-e024-11e8-85b5-f6ecaf4c4052.jpg)

### Supported browser

|Platform|Browser|
|:---:|:---:|
|iOS11 or later|Safari only|
|Android|Need support WebRTC and WebGL|

## Thankyou Watch this repository!
ARnenga is operation on Github. If you interested this project, 
Please try using [ARnenga](https://seiyahazama.github.io/ARnenga).

AR marker is : [https://seiyahazama.github.io/ARnenga/Marker/marker.png](https://seiyahazama.github.io/ARnenga/Marker/marker.png)

## Have a good year!
Have a good year.