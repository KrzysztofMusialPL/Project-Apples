# Project-Apples
Development of a neural network model and an application forthe correct classification of 6 classes of apples based on a set of fruitphotos. Using VGG16 as an algorithm to work with graphical data.Keras and TensorFlow libraries, Google Collab environment.

The task was to recognize each of the 6 classes of apples, based on photographic documentation for each class.

The project uses the VGG16 deep convolutional network to create a neural network model that will recognize each of the 6 classes of apples based on photos, with the greatest possible efficiency. The measure of effectiveness were metrics such as: Accuracy, precision, recall, f1-score. Very high efficiency was achieved - accuracy level over 99% for each class.

The Keras library and Google Collab were used to train the neural network model, test and verify it using selected metrics. The training of the model was carried out using the runtime environment: GPU hardware accelerator, T4 graphics processor.

Data source - Kaggle, baza Fruit Recognition (https://www.kaggle.com/datasets/chrisfilo/fruit-recognition).

Kaggle date set description: "The database used in this study is comprising of 44406 fruit images, which we collected in a period of 6 months. The images where made with in our lab’s environment under different scenarios which we mention below. We captured all the images on a clear background with resolution of 320×258 pixels. We used HD Logitech web camera to took the pictures. During collecting this database, we created all kind of challenges, which, we have to face in real-world recognition scenarios in supermarket and fruit shops such as light, shadow, sunshine, pose variation, to make our model robust for, it might be necessary to cope with illumination variation, camera capturing artifacts, specular reflection shading and shadows. We tested our model’s robustness in all scenarios and it perform quit well.
All of images were stored in RGB color-space at 8 bits per channel. The images were
gathered at various day times of the day and in different days for the same category. These
features increase the dataset variability and represent more realistic scenario. The Images had
large variation in quality and lighting. Illumination is one of those variations in imagery. In fact,
illumination can make two images of same fruit less similar than two images of different kind
of fruits. We were used our own intelligent weight machine and camera to captured all images.
The fruit dataset was collected under relatively unconstrained conditions. There are also images
with the room light on and room lights off, moved the camera and intelligent weight machine
near to the windows of our lab than open windows, closed windows, open window curtains,
closed curtains. For a real application in a supermarket, it might be necessary to cope with
illumination variation, camera capturing artifacts, specular reflection shading and shadows.
Below are the few conditions which we were considered during collected dataset.

Pose Variations with different categories of fruits
Variability on the number of elements of fruits
Used HD camera with 5-megapixel snapshots
Same color but different Category fruits images with illumination variation
Cropping and partial occlusion
Different color same category fruit images
Different lighting conditions (e.g. fluorescent, natural light some of the fruits shops
and supermarkets are without sunshine so it can easily affect the recognition system
Six different kind of apple fruit images
Three categories of mango fruit with specular reflecting shading and shadows
Three categories of Kiwi fruit images
Natural and artificial lighting effect on images
Partial occlusion with hand"
