# Image_Recognition_Classifier


1. Install Docker
2. Install Tensorflow
docker run -it gcr.io/tensorflow/tensorflow:latest-devel

3. Download images from google images using 'chrome addon'
4. Move images to tensorflow
docker run -it -v $HOME/tf_files/star_wars/ gcr.io/tensorflow/tensorflow:latest-devel
5. Retrain model
python ./tensorflow/examples/image_retraining/retrain.py
