# 头像加圣诞帽

## 1. 介绍

这是一个为头像加上圣诞帽子的简单程序，基于openCV和dlib。  

简单思路就是使用dlib检测器检测人脸，标注眼睛关键点，根据人脸进行帽子大小调整将人脸框上相对位置取出，进行圣诞帽的穿戴。  

## 2. 要求

Python 2.7

openCV  

dlib

## 3. 运行

python add_hat.py filename

> 参数filename 是自己的正脸照片（格式jpg），建议放在同一目录下。





