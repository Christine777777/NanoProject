# NanoProject
Training images for left and right arrows.

# training commands

```
docker/run.sh
python3 train.py --model-dir=models/Arrows data/Arrows
python3 onnx_export.py --model-dir=models/Arrows
```
