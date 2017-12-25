# 头像加圣诞帽

## 1. 介绍

这是一个为头像加上圣诞帽子的简单程序，基于openCV和dlib。  

简单思路就是使用dlib检测器检测人脸，通过获取眼睛关键点，根据人脸进行帽子大小调整将圣诞帽在人脸框上相对位置进行穿戴。  

## 2. 要求

Python 2.7

openCV  

dlib

## 3. 运行

python add_hat.py filename

> 参数filename 是自己的正脸照片（格式jpg），建议放在同一目录下。

## 4. 运行结果

![https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=false&word=%E5%91%A8%E6%9D%B0%E4%BC%A6&step_word=&hs=2&pn=1&spn=0&di=70810097820&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=246690743%2C2562283612&os=3665139541%2C291722614&simid=3436391278%2C173318048&adpicid=0&lpn=0&ln=3898&fr=&fmq=1514213424351_R&fm=&ic=undefined&s=undefined&se=&sme=&tab=0&width=&height=&face=undefined&ist=&jit=&cg=star&bdtype=0&oriquery=&objurl=http%3A%2F%2Fcimg2.163.com%2Fcatchimg%2F20090930%2F8458904_45.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3F1t2t_z%26e3B8mn_z%26e3Bv54AzdH3FalAzdH3FalnaAzdH3FamAzdH3FcKEIMSSCaa8m8bJ8_8m_z%26e3Bip4s&gsm=&rpstart=0&rpnum=0]()



