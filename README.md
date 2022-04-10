# Classificador de Imagens com YOLOv4-tiny

Implementação de um sistema de classificação de objetos para utilização em um sistema embarcado, utilizado para inferências em novas imagens.

## 🚀 Requirements (and how to install dependencies)

-This step very well documented in the AlexeyAB github (https://github.com/AlexeyAB/darknet#requirements-for-windows-linux-and-macos) in the main folder

-Download the dataset in (https://drive.google.com/file/d/1KHHGdAUjtNMXuUg-QKsIPyBWn-f3hU45/view?usp=sharing) and unzip in the main folder

-To set the dataset in the right form, download (https://github.com/jakkcoder/training_yolo_custom_object_detection_files) insise the custom_data folder
-Change the 'full_path_to_images' to the right path in both scripts and run. The dataset will be split in train and test.

### 🔧 Configuring YOLOv4-tiny

Download the model and weight from (yolov4-tiny.cfg - 40.2% mAP@0.5 - 371(1080Ti) FPS / 330(RTX2070) FPS - 6.9 BFlops - 23.1 MB: yolov4-tiny.weights)

Read and follow the instructions in AlexeyAB github, more precisely the How to train (to detect your custom objects) section.



