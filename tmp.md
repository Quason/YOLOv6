``` bash
python tools/train.py --batch 20 --conf configs/yolov6s6_finetune_cqy.py --data data/dataset_plane.yaml --img-size 768 --device 0 --epochs 100 --eval-interval 1 --check-labels --output-dir ./runs/train --stop_aug_last_n_epoch 5
```
