## 添加自己的ai模型 实现自动打标签

1. 按照文档配置 在/X-AnyLabeling/anylabeling/configs/auto_labeling/ 添加.yaml配置文件

```
type: yolov8
name: circle-0202
display_name: 3C circle
model_path: anylabeling/configs/auto_labeling/circle.onnx
nms_threshold: 0.45
confidence_threshold: 0.25
classes:
  - circle
```

2. model_path 下面需要放自己的.onnx 的模型
