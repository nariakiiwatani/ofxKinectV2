ofxKinectV2
===========

An addon for the new Kinect For Windows V2 sensor. 
Based on the excellent work by the https://github.com/OpenKinect/libfreenect2 team ( @JoshBlake @floe and @christiankerl plus others ) 

Notes:
- Currently only supports one Kinect V2 at a time. 
- Kinect needs to have flashed firmware ( this currently needs to be done on Windows 8 ) 
- Requires USB 3 port on machine. 
- Only tested on OS X though Win / Nix should be possible too with patched libusb ( see: https://github.com/OpenKinect/libfreenect2/blob/master/depends/README.depends.txt ) 
- If you have the ofxKinect ( v1 ) addon in your project remove the ofxKinect libusb lib and use the one that comes with this repo instead. 
- Depth decoding is not at 30fps as it is decoded on the CPU - GPU decoding is possible, but not stable currently with OF. 


Huge thanks to @christiankerl for a lot of the recent changes that made this work well on OS X. 