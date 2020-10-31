基于OpenCV调用USB摄像头进行图像捕捉  
利用OpenCV和Python调用USB摄像头捕捉图像并定时保存  
基于Python实现：调用usb接口的摄像头，将摄像头采集到的视频每三十分钟截图存储一次，保存在特定的地址下。 这里需要调用opencv，自学  
在电脑上实现后需要移植到树莓派上面实现  
#########################################以下是王瑞基的实现方式案例############################################  
实现功能：调用摄像头录制视频，每5s保存一次图像，人脸检测，检测到人脸后进行框选  
开发环境：Win10+Visual Studio Code  
语言版本：Python 3.6.5  
在win10的命令行中使用pip下载OpenCV包，由于国外源下载速度十分缓慢，这里建议使用国内清华大学镜像源，命令是：pip install -i https://pypi.tuna.tsinghua.edu.cn/simple opencv-python  
人脸检测的数据集在OpenCV中自带，如果没有可以使用我上传到仓库的xml文件  
