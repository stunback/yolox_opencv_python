# yolox_opencv_python
This is a project to deploy YOLOX depending on opencv_python only.
  
仅依赖于opencv python环境的yolox模型推理部署代码  
  
The YOLOX origin repo:https://github.com/Megvii-BaseDetection/YOLOX.git  

# Environments
```
opencv_python>=4.3  
opencv_contrib_python>=4.3  
```

# Usage
```
git clone https://github.com/stunback/yolox_opencv_python.git
cd src
python main_yolox.py
```

# Model Inference Speed
Hardware:      i7-10875H  
  
yolox_nano(416)  onnx=27.1ms  
yolox_tiny(416)    onnx=43.1ms  
yolox_s(640)        onnx=130.2ms  
yolox_x(640)        onnx=750ms  

# Others
Blogs about yolov5, yolox and nanodet:  
https://blog.csdn.net/qq_41035283/article/details/119150751  