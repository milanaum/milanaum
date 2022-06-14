1.import cv2
img=cv2.imread('dog2.jfif',0)
cv2.imshow('image',img)
cv2.waitKey(0)
cv2.destroyAllWindows()

2.import matplotlib.image as mping
import matplotlib.pyplot as plt
img=mping.imread('dog2.jfif')
plt.imshow(img)
<matplotlib.image.AxesImage at 0x20d2d773e20>


3.import cv2 from PIL import image
img=image open('dog2.jfif')
img=img.rotate(180)
img.show()
cv2.waitKey(0)
cv2.destroyAllWindows()

4.from PIL import ImageColor
img1=ImageColor.getrgb("yellow")
print(img1)
img2=ImageColor.getrgb("red")
print(img2)
img3=ImageColor.getrgb("green")
print(img3)

5.from PIL import Image
img=Image.new('RGB',(200,400),(0,128,0))
img.show()

6.import cv2
import matplotlib.pyplot as plt
import numpy as np
img=cv2.imread('dog2.jfif')
plt.imshow(img)
plt.show()
img=cv2.cvtColor(img,cv2.COLOR_BGR2RG)
plt.show()
img=cv2.cvtColor(img,cv2.COLOR_RGB2HSV)
plt.show()


7.from PIL import Image
image=Image.open('dog2.jfif')
print("Filename:",image.filename)
print("Format:",image.format)
print("Mode:",image.mode)
print("Size:",image.size)
print("Width:",image.width)
print("Height:",image.height)
image.close()



