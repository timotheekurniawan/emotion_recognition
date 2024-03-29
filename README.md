# emotion_recognition

Github Repository for Group 1's COMP3359 Project.

Group Members:
- Marco Brian Widjaja (UID: 3035493024)
- Timothee Wirasaputra Kurniawan (UID: 3035663069)

This repository consists of all the Jupyter Notebooks/Google Colabs we ran for testing and experimenting on various models for our project. Basically, these were the models we experimented:

1. VGG architecture with undersampling of dataset
https://github.com/timotheekurniawan/emotion_recognition/blob/master/vgg_undersampling.ipynb
2. VGG architecture with oversampling of dataset
https://github.com/timotheekurniawan/emotion_recognition/blob/master/vgg_oversampling.ipynb
3. VGG architecture with class weights method
https://github.com/timotheekurniawan/emotion_recognition/blob/master/fer2013_vggface_classweights.ipynb
4. Resnet50 architecture with undersampling of dataset
https://github.com/timotheekurniawan/emotion_recognition/blob/master/resnet_undersampling.ipynb
5. Resnet50 architecture with oversampling of dataset
https://github.com/timotheekurniawan/emotion_recognition/blob/master/resnet50_fer2013_freezed.ipynb
6. Resnet50 architecture with class weights method
https://github.com/timotheekurniawan/emotion_recognition/blob/master/fer2013_resnet_classweights.ipynb
7. InceptionResNet architecture with undersampling of dataset
https://github.com/timotheekurniawan/emotion_recognition/blob/master/inceptionresnet_undersampling.ipynb
8. InceptionResNet architecture with oversampling of dataset
https://github.com/timotheekurniawan/emotion_recognition/blob/master/inceptionresnet_oversampling.ipynb
9. InceptionResNet architecture with class weights method
https://github.com/timotheekurniawan/emotion_recognition/blob/master/fer2013_inceptionnet_classweights.ipynb

For the final version of our model, we decided to use (9) InceptionResNet architecture with class weights method, which in the actual implementation, gives us the best results.
This can be found https://github.com/timotheekurniawan/emotion_recognition/blob/master/v2_inception_classweights.ipynb

Other files:
1. trained_models: all the saved models from training
2. camera_face_detection.ipnyb: demonstration of the facial detection with desktop camera using OpenCV
3. haarcascade_frontalface_default.xml : Haar Cascade Classifier to detect objects (faces in our case)

![Capture1](https://user-images.githubusercontent.com/61657963/115520010-4cbdf180-a2bc-11eb-8966-2e02d4d30c42.JPG)


https://user-images.githubusercontent.com/61657963/150637149-93fe9cd2-a35b-419f-a94c-df0909f7d6bb.mp4

