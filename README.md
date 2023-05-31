# ml5-handpose

This is the working repository for the handpose feature of ml5.
The old [handpose](https://github.com/tensorflow/tfjs-models/tree/master/handpose) model is upgraded to the new [Hand-Pose-Detection](https://github.com/tensorflow/tfjs-models/tree/master/hand-pose-detection) model by MediaPipe. This new Tensorflow.js model wraps the [MediaPipe JS Solution](https://developers.google.com/mediapipe/solutions/vision/gesture_recognizer/web_js) which to provide a familiar interface. The implementation of the ml5 feature wraps the Tensorflow.js model which then wraps the MediaPipe model.

The new model provide more accurate tracking and better performance. Additionally, it can track multiple hands at once.

## Usage

This build uses node version 18.15.0 and npm version.
Install nvm and run the following commands：

```
nvm install 18.15
nvm use 18
```

To build the library, run the following commands:
```
yarn
npm run build
```

Open the 'example/index.html' in the browser with Live Server to run the build with a p5.js sketch.

