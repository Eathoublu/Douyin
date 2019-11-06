抖音用户视频下载器（可去水印）
======================
![](https://img.shields.io/badge/Python-3.7.2-green.svg) ![](https://img.shields.io/badge/requests-2.20.0-green.svg) ![](https://img.shields.io/badge/PyExecJS-1.5.1-green.svg)     
### 
|Author|:sunglasses:Esbiya:sunglasses:|
|---|---
|Email|:hearts:18829040039@163.com:hearts:|
|QQ|:hearts:2995438815:hearts:

****
### :dolphin:声明
### 本项目仅用于学习交流, 请遵守当地法律法规, 勿用于任何商业用途, 否则后果自负！感谢大家！
### 如若涉及侵权，请邮件或qq联系删除! 

## :dolphin:运行环境
```
Version: Python3
```
## :dolphin:安装依赖库
```
pip install -r requirements.txt
```


## :dolphin:运行
```
python downloader.py
```

## :dolphin:说明

- **本地 js 生成需要传入用户ID。 获取方式: APP中进入用户主页点击分享复制短链接, PC端打开, 获取用户ID即原始链接中/share/user/后的数字。**

- **需要传入关键的全局变量 tac , 才能生成正确的 _signature 。获取方式: 用户主页源码正则匹配获取。**

- **视频链接获取不稳定, 需要多次尝试。**

- **更新 Flask API 服务, 可部署为线上服务, 传入用户ID等参数即可返回视频下载地址列表。**
  
## :dolphin:效果
--------
![image](https://github.com/Esbiya/Douyin/blob/master/view.gif)


## :dolphin:**最后**
> **如果本项目帮助到了您, 请您给个 Star, 感谢!**:cupid::cupid:
