# Face_Detection_Filters

This is a web application for basic image processing and facial feature detection built with Streamlit and OpenCV. The application uses Streamlit to create a user interface that allows users to upload an image and select the desired operation. It then leverages OpenCV's pre-trained classifiers to detect facial features in the image. Finally, it displays the original and processed images.


# Features

## Image Enhancement:

Convert to grayscale
Adjust contrast
Adjust brightness
Apply blurring
Object Detection:

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
