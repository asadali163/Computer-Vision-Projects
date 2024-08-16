# Computer-Vision-Projects

### CV_face_detection.ipynb
This notebook covers several face detection techniques:
- Detecting faces using the Haarcascade method with OpenCV.
- Detecting faces using the Histogram of Oriented Gradient (HOG) method with dlib.
- Detecting faces using a Convolutional Neural Network (CNN).
- Real-time face detection using a webcam.

### CV_face_recognition.ipynb
This notebook includes the following tasks:
- Utilizing the open-source Yale Face Database.
- Recognizing faces using the Local Binary Pattern Histogram (LBPH) algorithm.

### CV_transfer_learning_classification.ipynb
This notebook performs the following tasks:
- Utilizes the Bart and Homer character dataset for a classification task.
- Uses ResNet50 as the base model.
- Applies transfer learning for classification.
- Implements fine-tuning for improved classification results.
- Fine-tuning yields significantly better results than simple transfer learning.

### CV_image_compression_AE.ipynb
This notebook focuses on image compression using autoencoders and includes the following:
- Utilizes the MNIST digit dataset.
- Applies a linear autoencoder for image compression.
- Decodes the compressed images and compares the results using plots.
 
### CV_image_compression_CNN.ipynb
This notebook focuses on image compression using CNN autoencoders and includes the following:
- Utilizes the Fashion MNIST dataset.
- Employs a CNN-based complex autoencoder structure for image compression.
- Compares the results using plots.

### CV_object_detection_YOLO.ipynb
This notebook utilizes the YOLOv4 model for object detection in images and videos using the Darknet framework. The following tasks are performed:
- The Darknet framework is used, which is easier to work with compared to OpenCV.
- Objects are detected in both images and videos.

### CV_deep_dream.ipynb
This notebook utilizes the Inception model for creating Deep Dream images. The notebook includes:
- Using the Inception model as a base.
- Creating dramatic images, leveraging the fact that the Inception model is trained on the ImageNet dataset.

### CV_neural_transfer.ipynb
This notebook uses the VGG19 model as a base for style transfer between images. The process involves:
- Accepting a style image and a content image.
- Producing a result where the style from the style image is transferred to the content image.
