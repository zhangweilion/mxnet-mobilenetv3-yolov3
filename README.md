# mxnet-mobilenetv3-yolov3
This repo implements base on   MXNet [Gluoncv](https://github.com/dmlc/gluon-cv) API
The model is base on mobilenetv3  and adding detect head with yolov3
I train it  in dataset voc(voc2012) and get MAP-0.7956  with no pre-processing with mixup  or muti-scale input training or warmup training skills ,you might user the pre-training model we provided to training more accurate models with more skills.
