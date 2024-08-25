# Authentify-AI-
Authentify AI: Long Range attention for deepfake detection 

The following is a major project submitted by students of SWCET, Hyderabad in June 2024 

With the growth and widespread use of social media platforms like YouTube, Instagram, WhatsApp, and others, there are now more photographs being uploaded and shared. These images are used to disseminate information to a large audience, aiding in the large-scale formation of public opinion. Numerous false images are shared on these platforms every day as a result of the inherent ability of the general public to form opinions and the accessibility of photo and video editing software. In addition to social media, manipulated images are also used in legal proceedings, academic publications, literary works, etc. The practice of altering the original image to conceal important details or to display false information is known as image forgery . Due to the extensive use of photos and the serious repercussions of fabricating images, numerous different sorts of studies are being done to identify manipulated photographs. Active methods of detecting forgeries, such as electronic signatures and watermarking, have the limitation of necessitating the presence of the watermark or sign to be inserted into the image beforehand, which restricts the situations in which this technique would be effective.

We have made a deep fake detector with the use of YOLOv5 and CNN model to detect and classify the images on whether they have been tampered and can even classify the tampering into 
1. Splicing: This image alteration technique involves copying and pasting a few or all of the image's sections onto another image. It can be applied in order to give a scene an extra component.
2. Copy-move: It can be used for the purpose of adding false information or hiding information. 
3. Removal: This type of alteration fills in the empty areas of an image by, for instance, employing inpainting techniques. It can be applied to the removal of things with the goal of concealing information.

![image](https://github.com/user-attachments/assets/c0dc7b3a-b6a9-44dc-99e1-843719488b59)

Requirements
absl-py==2.1.0
asgiref==3.7.2
astunparse==1.6.3
cachetools==5.3.3
certifi==2024.2.2
charset-normalizer==3.3.2
colorama==0.4.6
cssselect==1.2.0
cssutils==2.7.1
cycler==0.11.0
Django==3.2.25
flatbuffers==24.3.7
fonttools==4.38.0
gast==0.4.0
gitdb==4.0.11
GitPython==3.1.42
google-auth==2.29.0
google-auth-oauthlib==0.4.6
google-pasta==0.2.0
grpcio==1.62.1
h5py==3.8.0
idna==3.6
importlib-metadata==6.7.0
joblib==1.3.2
keras==2.11.0
kiwisolver==1.4.5
libclang==18.1.1
lxml==5.1.0
Markdown==3.4.4
MarkupSafe==2.1.5
matplotlib==3.5.3
numpy==1.21.6
oauthlib==3.2.2
opencv-python==4.9.0.80
opt-einsum==3.3.0
packaging==24.0
pandas==1.3.5
Pillow==9.5.0
premailer==3.10.0
protobuf==3.19.6
psutil==5.9.8
py-cpuinfo==9.0.0
pyasn1==0.5.1
pyasn1-modules==0.3.0
pyparsing==3.1.2
python-dateutil==2.9.0.post0
pytz==2024.1
PyYAML==6.0.1
requests==2.31.0
requests-oauthlib==1.4.0
rsa==4.9
scikit-learn==1.0.2
scipy==1.7.3
seaborn==0.12.2
six==1.16.0
smmap==5.0.1
sqlparse==0.4.4
tensorboard==2.11.2
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.1
tensorflow==2.11.0
tensorflow-estimator==2.11.0
tensorflow-intel==2.11.0
tensorflow-io-gcs-filesystem==0.31.0
termcolor==2.3.0
threadpoolctl==3.1.0
torch==1.13.1
torchvision==0.14.1
tqdm==4.66.2
typing_extensions==4.7.1
ultralytics==8.0.145
urllib3==2.0.7
Werkzeug==2.2.3
wrapt==1.16.0
yagmail==0.15.293
zipp==3.15.0
