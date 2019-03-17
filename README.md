# Camvas

A simple HTML5 library to stream a webcam video to a `<canvas>` object. 

Uses WebRTC (getUserMedia), Canvas and HTML5 Video.

Check out a sample application, too: [camvas_photobooth](http://cbrandolino.github.io/camvas_photobooth/).

## Features
* Webcam profile support ( qvga, vga, hd, fullhd, 4k, 8k )
* drawImage tools

## Config
| Name  | Description | Default value |
| ------------- | ------------- |---|
| mode  | Set camera profile  | vga |
| mode_resize  | Resize canvas by by profile width & height | true |

## Example

```javascript
var ctx = document.querySelector('canvas').getContext('2d');
var myCamvas = new camvas(ctx);
```
See https://diewland.github.io/camvas/

## TODO
* change config `mode` to `video_mode`
