## YOLO

| version | provided by | source | download URL |
| ------- | ----------- | ------ | ------------ |
| v5 | ultralytics | [3.1 models/utils URL](https://github.com/ultralytics/yolov5/archive/master.zip) | - [models](yolo/v5/ultralytics/v3.1/models.tar.gz)<br>- [utils that model depends on](yolo/v5/ultralytics/v3.1/utils.tar.gz) (--exclude=google_app_engine utils/)<br> |
| | | [3.1 hubconf](https://github.com/ultralytics/yolov5/tree/v3.1) | - [hubconf](yolo/v5/ultralytics/v3.1/hubconf.py)<br> |
| | | [3.1 v5s URL](https://github.com/ultralytics/yolov5/releases/download/v3.1/yolov5s.pt) | - [v5s weights](yolo/v5/ultralytics/v3.1/weights/yolov5s.pt)<br> |
| v5 | ultralytics | master #9f5a18b [models/utils URL](https://github.com/ultralytics/yolov5/commit/9f5a18bb8095cf2af8872640a1ed6fa6dc941fc7) | - [models](yolo/v5/ultralytics/9f5a18b/models.tar.gz)<br>- [utils that model depends on](yolo/v5/ultralytics/9f5a18b/utils.tar.gz) (--exclude=google_app_engine utils/)<br>

### Packaging
```
tar cvf ../models.tar models 
tar cvf ../utils.tar --exclude=google_app_engine utils/
```
