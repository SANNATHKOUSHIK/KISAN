# KISAN
## Documentation

kisan is designed to accuratley detect crop diseases within seconds. Kiasn detects problem in real time and shows accurate treatment solutions. Here is the best home farming app.

kisan is a user friendly app that helps your plant to grow disease free. You can easily find the solution for your plant and get suggestions for healthy growth. <!-- kisan helps you to make homemade fertilizers. -->
### Features
KISAN trained in deep CNN with many layers to predict the diseases with high accuracy. It can also provide the solutions for insects and pathogens. Kisan was trianed over 100 globally identified crop diseases. Kisan takes probabilties for the diseases to find the interlinked causes for the disease so that the solutions cures the plant quicker.

![Disease Detection](https://bitrefine.group/images/1920x870/damaged_leaves_1920x870.jpg)

### Technologies used
* python
* kivy
* tenserflow/keras
* opencv

To install the modules
```
pip install kivy
pip install tenserflow
pip install opencv-python
```
kivy [documentation](https://kivy.org/doc/stable/gettingstarted/intro.html "kivy")

tenserflow [documentation](https://www.tensorflow.org/api_docs/python/tf "tensorflow")

opencv [documentation](https://docs.opencv.org/4.x/d1/dfb/intro.html "opencv")
### APK

To build apk file I used buildozer. Buildozer currently works only in Linux and macOS (You can still use it on Windows via WSL), and can significantly simplify the apk build.
To install buildozer
```
pip install buildozer
```
This will install buildozer in your system. Afterwards, navigate to your project directory and run:
```
buildozer init
```
This creates a buildozer.spec file controlling your build configuration. You should edit it appropriately with your app name etc. You can set variables to control most or all of the parameters passed to python-for-android.
Finally, plug in your android device and run:
```
buildozer android debug deploy run
```
to build, push and automatically run the apk on your device.

buildozer [documnentation](https://kivy.org/doc/stable/guide/packaging-android.html "buildozer")

You can get buildozer at [https://github.com/kivy/buildozer](https://github.com/kivy/buildozer)
