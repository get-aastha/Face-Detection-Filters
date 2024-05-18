# Face_Detection_Filters

This is a web application for basic image processing and facial feature detection built with Streamlit and OpenCV. The application uses Streamlit to create a user interface that allows users to upload an image and select the desired operation. It then leverages OpenCV's pre-trained classifiers to detect facial features in the image. Finally, it displays the original and processed images.


# Features

## Image Enhancement:

Convert to grayscale

Adjust contrast

Adjust brightness

Apply blurring

Object Detection


## Image Detection:

Detect faces

Detect eyes

Detect nose

Detect mouth

Detect ears


# Steps

1) Clone the Colab File on you perosnal Google Colab account.
2) Go to Runtime -> Run All. This will execute all the blocks of code.
3) Once you finish exceuting the last block i.e !streamlit run app.py & npx localtunnel --port 8501, it will generate a link labeled 'your url is'
4) Click on the url. You will be redirected to a local tunnel webpage asking you for a pass.
5) In your colab file, when you run the second last block i.e !wget -q -O - ipv4.icanhazip.com, you would have gotten an ip address as output. Paste this ip adrress in the local tunnel website and hit Enter.
6) Tadaaa!! Streamlit is now running and you can upload any picture of your choice and get started with exploring the filters.

# Screenshots

Original Image Upload
![image](https://github.com/get-aastha/face_detection_filters/assets/108509128/6db956ca-02f0-44fe-8198-c866a9270b67)

Manipulating Grayscale Filter
<img width="960" alt="2024-05-18 (3)" src="https://github.com/get-aastha/face_detection_filters/assets/108509128/38fb8c42-6ec5-438f-ab94-24df48474122">

Manipulating Brightness Filter
<img width="960" alt="2024-05-18 (4)" src="https://github.com/get-aastha/face_detection_filters/assets/108509128/32476d74-ad4c-4fc5-bf10-42e3db11b05e">

Manipulating Contrast Filter
<img width="960" alt="2024-05-18 (5)" src="https://github.com/get-aastha/face_detection_filters/assets/108509128/3f8712ac-b225-4422-b6ab-ab663a47c43d">

Face Detection
<img width="960" alt="2024-05-18 (7)" src="https://github.com/get-aastha/face_detection_filters/assets/108509128/e141dc3b-5014-44f9-9447-567670621f60">
