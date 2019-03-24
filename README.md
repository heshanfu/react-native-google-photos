# react-native-google-photos
 > Grabs Streaming &amp; Downloader Link Google Photos & Blogger .Dll

## Toc

* [Installation](#installation)
* [Usage](#usage)
* [Next](#next)

## Installation

Using npm:

```shell
npm install --save react-native-google-photos
```

or using yarn:

```shell
yarn add react-native-google-photos
```

## Usage
> Support [Google Photos](http://photos.google.com) & [Blogger](https://www.blogger.com)
```js
import Grab from 'react-native-google-photos';

var photos = "https://photos.google.com/share/AF1QipMTEPAiVF8t0YqLukflnOSQjwfd8ARIoT2h37AXvYO1uaWodbeiFoBUDuD_19tEbg/photo/AF1QipPA2Bq0JlAR9LoGD3mogsxSb9OZWEG4XqBDD4Rv?key=cjhUT0xrZjM5NGN2SVRLOVptZU5SMUlKV0lQYWpB";

var blogger = "https://prikate09.blogspot.com/2017/10/all-ani-29-oktober-2017-413.html"

//Google Photos
Grab.Photos(photos).then(res=>{
    console.log(res); 
})

//Blogger
Grab.Blogger(blogger).then(res=>{
    console.log(res)
})


```
## Require Google Photos

* Allow the google photos to public access folder
* Only supports video urls not folder urls

## Next
- [x] Add `Streaming & Download` [Google Photos](https://photos.google.com) 
- [x] Add `Streaming & Download ` [Blogger](https://www.blogger.com)
- [ ] Add `Streaming Only`  [Cloudvideo.tv](https://cloudvideo.tv/) 
