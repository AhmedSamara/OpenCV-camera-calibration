Code branched from:

http://docs.opencv.org/2.4/doc/tutorials/calib3d/camera_calibration/camera_calibration.html



# How to use:   
(Authors note: this was just a collection of useful openCV snippets. It has not been touched or maintained in a long time and may be a red herring, I recommend going directly to the opencv docs for help instead of using anything here).

`cmake .`  
`make`    
and then:  `./CalibrateCamera filename.xml`  
The file should exist before you run this.

also be sure to configure the `.xml` file with the data you want, whether you're calibrating with a chessboard, or via a camera or with video.

