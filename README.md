# sample-tensorflow-research-models

Try to make this example work with Tensorflow 2.0.
https://github.com/tensorflow/models/tree/master/research/object_detection

Instructions
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2.md

git clone https://github.com/tensorflow/models.git

docker build -f research/object_detection/dockerfiles/tf2/Dockerfile -t od .
docker run -it od
