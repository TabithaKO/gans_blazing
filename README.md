# gans_blazing
I use face parsing algorithms and GANs to create visually interesting videos. 

## Dlib.ipynb 💫 
The Dlib algorithm allows you to perfrom landmark detection on a face. I edited the code to highlight 8 uniqe landmarks but the original model can definitely highlight many more models. The notebook allows you to implement this model on a single image or a video.

## FaceParse_CelebA.ipynb 💫  
The face parse model was trained on celebA-HQ. There are 18 unique classes that are segmented on the face image.The notebook allows you to implement this model on a single image or a video.

## Mediapipe.ipynb 💫  
This a landmark detection model with over 400 landmarks (so you can get really precise with your landmarks). Read more from the authors [here](https://google.github.io/mediapipe/solutions/face_mesh.html) The notebook allows you to perfrom the landmark detection on a video and generate side by side comparison. The original notebook by a separate author is [here](https://colab.research.google.com/github/kevinash/awesome-ai/blob/main/notebooks/5_FacesAndExpressions/MediaPipe_Face_Mesh.ipynb)

## ICFace.ipynb 💫  
This is a face reenactment model. The notebook implements the code specified in the [authors' repository](https://github.com/Blade6570/icface) with some minor changes to allow it to run smoothly on Google Colab.

## StarGAN_V2.ipynb 💫
This is a style transfer model that allows us to transfer style like hairstyle, skin color, makeup etc from a reference image to a source image. The pretrained weights are provided by myself based on a model trained on 4 domains. The rest of the code is supplied by the [original authors](https://github.com/clovaai/stargan-v2-tensorflow).

## ImpersonatorGAN_plus_plus.ipynb 💫
This is a pose transfer model that allows us to transfer body pose from a reference video to a source image. I added nothing besides a comment on where to reference your custom inputs in the code. The notebook is a replica of the one provided by the authors [here](https://github.com/iPERDance/iPERCore)


## OpenFace.ipynb 💫
This is a landmark detection model that allows us to detect 98 landmarks as well as gaze on an image. The notebook is based on the [original authors'](https://github.com/TadasBaltrusaitis/OpenFace) notebook however I change the test video from a youtube video to a custom video that one uploads to Google Colab. 

