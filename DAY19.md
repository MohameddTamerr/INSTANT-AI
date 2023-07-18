# DAY19
### Kinds Of Filters To Put In Each Photo And Usage Of Each:
1)Median Filter

2)Laplacian Filter

3)Gaussian Filter

4)Neighbourhood Average Filter

5)BOX Filter
### Libraries For Computer Vision In Python
1)fastai

2)IPSDK

3)Imutils

4)Keras

5)Matplotlib

6)OpenCV

7)Pytessarct

8)PyTorchCV

9)Scikit-Image

10)SimpleCV 
###How To Read Video In Image and Audio By Python:
import cv2

import numpy as np

#ffpyplayer for playing audio

from ffpyplayer.player import MediaPlayer

video_path="../L1/images/Godwin.mp4"

def PlayVideo(video_path):

    video=cv2.VideoCapture(video_path)
    
    player = MediaPlayer(video_path)
    
    while True:
    
        grabbed, frame=video.read()
        
        audio_frame, val = player.get_frame()
        
        if not grabbed:
        
            print("End of video")
            
            break
            
        if cv2.waitKey(28) & 0xFF == ord("q"):
        
            break
            
        cv2.imshow("Video", frame)
        
        if val != 'eof' and audio_frame is not None:
        
            #audio
            
            img, t = audio_frame
            
    video.release()
    
    cv2.destroyAllWindows()
    
PlayVideo(video_path)
