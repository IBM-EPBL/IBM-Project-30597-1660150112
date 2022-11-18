# IBM-Project-30597-1660150112

Team Members:

   1.Vaishnavi Parvathy N
   2.Swetha E
   3.Sowmiya M
   4.Sindhuja C
   
                                                 "A Gesture-based Tool for Sterile Browsing of Radiology Images"

             In this project we use gestures to browse images obtained during radiology. Gestures refer to non verbal forms of communication made using hands.
             
             Humans are able to recognize body and sign language easily. This is possible due to the combination of vision and synaptic interactions that were formed along brain development . In order to replicate this skill in computers, some problems need to be solved: how to separate objects of interest in images and which image capture technology and classification techniques are more appropriate, among others.
 
             In this project Gesture based Desktop automation, First the model is trained pre-trained on the images of different hand gestures, such as showing numbers with fingers as 1,2,3,4. This model uses the integrated webcam to capture the video frame. The image of the gesture captured in the video frame is compared with the Pre-trained model and the gesture is identified. If the gesture predicts is 0 - then images is converted into rectangle, 1 - image is Resized into (200,200), 2 - image is rotated by -45॰, 3 - image is blurred, 4 - image is Resized into (400,400), 5 - image is converted into grayscale etc.

                       1. Defining our classification categories
                       2. Collect training images
                       3. Train the model
                   	   4. Test our model
