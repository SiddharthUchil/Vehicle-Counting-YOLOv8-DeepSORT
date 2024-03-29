# Vehicle counting system with Speed Estimation using YOLOv8 and DeepSORT

Vehicle counting provides critical information to traffic analysis problems
(like monitoring flow, peaks/jams, etc.) and other related traffic issues like highway management.
Having an good and accurate understanding of traffic flow can help for urban planners to be able
to make more informed decision to improve the general quality of life for the citizens. While there already exist numerous methods to
accomplishing the task already, from manually counting to special censors (and many other alternatives), developing
smart systems to automatically count in real time can be incredibly useful and save much time and effort.

## CLI: Object Detection + Tracking + Vehicle Counting + Speed Estimation

```
python predict.py model='name_of_your_model.pt' source='name_of_your_input_file.mp4' show=True
```

### You can train your model on a custom dataset using Roboflow notebook:

https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov8-object-detection-on-custom-dataset.ipynb

### Setting up the environment

```
pip install -e '.[dev]'

```

```
cd ultralytics/yolo/v8/detect

```

#### Download the DeepSORT folder and save under the same file path

```
https://github.com/nwojke/deep_sort

```

### Model Weights from Ultralytics offical page:

```
https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8l.pt
```

### RESULTS

#### Object Detection + Tracking + Vehicle Counting + Speed Estimation

https://github.com/SiddharthUchil/Vehicle_Counting_YOLOv8_DeepSORT/assets/36127139/1e24a9db-43ad-4e0b-8a70-ce452590a675


