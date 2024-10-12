* Run training script with configuration YAML file and checkpoints.
* The --ckpt_epoch option specifies how many epochs of checkpoints to use. By default, the latest one is used.
```
python train_ft.py maas_vmae2_multiclass.yaml ckpt/CHECKPOINT_NAME --output OUTPUT_NAME
```
