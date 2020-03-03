# openpose-darknet
Openpose implementation using darknet framework

<b>[Openpose]</b><p>
https://github.com/CMU-Perceptual-Computing-Lab/openpose

<b>[Darknet]</b><p>
https://github.com/pjreddie/darknet

<b>[Result]</b><p>
![demo](https://user-images.githubusercontent.com/16308037/34094455-333f678c-e408-11e7-9546-f8aeb3df39c2.jpg)

<b>[Benchmark]</b><p> 80x80x3 net input size:</br> 
  12 fps on Jetson Xavier</br>
  17 fps on Jetson TX2</br>
  36 fps on RTX2070

<b>[Weight file] (darknet version openpose.weight)</b><p>
https://drive.google.com/open?id=1BfY0Hx2d2nm3I4JFh0W1cK2aHD1FSGea</br>
https://www.dropbox.com/s/irz49dal2itzpox/openpose.weight

<b>[note]</b><p>
1. Darknet version openpose.cfg and openpose.weight are ported from COCO version 
  pose_deploy_linevec.prototxt and pose_iter_440000.caffemodel.
2. You could change net input width, height in openpose.cfg.
