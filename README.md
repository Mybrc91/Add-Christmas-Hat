# Add-Christmas-Hat

## Install on Windows
### install Visual Studio
### install cmake 
1. download cmake
2. set PATH on `cmake-root`\bin
### install python2.7 
### install numpy
1. `pip install numpy`
### install opencv 
1. download opencv
2. copy cv2.pyd from build\python\2.7\x86 or build\python\2.7\x64 to your-python-root\Lib\site-packages
### install boost
1. download boost1.61
2. run `bootstrap.bat` on `boost-root`\tools\build
3. run `b2 install` on `boost-root`\tools\build
4. run `b2 -a --with-python address-model=32 toolset=msvc runtime-link=static` on `boost-root`
5. set environment variables `BOOST_ROOT=boost-root` and `BOOST_LIBRARYDIR=boost-root\stage\lib`
### install dlib
1. download dlib
2. run `python setup.py install` on dlib-root
#### Add Christmas hat on one's head based on OpneCV and Dlib
#### You can download a trained facial shape predictor from [http://dlib.net/files/shape_predictor_5_face_landmarks.dat.bz2](http://dlib.net/files/shape_predictor_5_face_landmarks.dat.bz2)
---

<div>
<img src="https://github.com/LiuXiaolong19920720/Add-Christmas-Hat/blob/master/output.jpg" width="70%">
</div>

---
