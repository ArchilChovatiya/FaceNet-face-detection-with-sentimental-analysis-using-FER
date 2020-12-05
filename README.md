# FaceNet-Facedetection-with-Sentimental-analysis-using-FER
### Installation Python Libraries:
- Tensorflow (1.4.0)
- Scipy (0.17.0)
- Scikit-learn (0.19.1)
- Opencv (2.4.9.1)

### Process to train FaceNet model
- Place Dataset of images in folder containing Label same as person name and place it in ./train_img.
- After that run data_preprocess.py and then run train_main.py
- in ./pre_img you will find processed (cropped) images of faces.This images will used to train FaceNet model when train_main.py is runned.
- Here I have placed FER(Fecial expression recognition) model named model.h5 so you don't need to additionally train it.
- To utilize both FaceNet and FER model run Identify_face_with_sentimental_analysis.py

### Usage:
- Well this facenet is defined and implementation of facenet paper published in Arxiv (FaceNet: A Unified Embedding for Face Recognition and Clustering). And also contain the idea of two paper named as "A Discriminative Feature Learning Approach for Deep Face Recognition" and "Deep Face Recognition". For deep understanding about its concept you can follow upper paper. One also main part is that for genearating your own model you can follow this link Face Recognition using Tensorflow. David Sandberg have nicely implemnted you can also find it on Github for complete code and uses.


- To get more knowledge about Facial Expression Recognition visit https://github.com/ArchilChovatiya/Facial-Expression-Recognition.
- To get trained model of FER contact me @ chovatiya.archil@gmail.com
