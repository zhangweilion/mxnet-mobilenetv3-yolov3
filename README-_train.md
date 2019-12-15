root@ec0c6e1ef34f:~/project/train-yolov3# python3  scripts/detection/yolo/train_yolo3.py --gpus=0,1,2,3  --network mobilenetv3.1 --dataset voc --resume yolo3_mobilenetv3.1_voc_0190_0.4315.params --start-epoch 400  --epochs  500



#train car
python3  scripts/detection/yolo/train_yolo3.py --gpus=0,1,2,3  --network mobilenetv3.1 --dataset car --start-epoch 0  --epochs  400

