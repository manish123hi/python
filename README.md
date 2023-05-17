# python
#to start a real time camera


import cv2               #for this u must had have to installed the opencv
                 
cap = cv2.VideoCapture(0)

while True:
  success,img=cap.read()  
  cv2.imshow("image",img)
  cv2.waitKey(1)
