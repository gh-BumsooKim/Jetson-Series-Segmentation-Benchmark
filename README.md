# Jetson-Nano-Segmentation-Benchmark

Segmentation Benchmark on Nvidia Jetson Nano

## Benchmark Task

- Instance Segmentation
- Semantic Segmentation

## Benchmark Method

Model Optimization : Pytorch Model -> ONNX Export -> TensorRT Optimization -> Nvidia Jetson Board Testing
Processing Time Measurement : Preprocessed-Image -> Timestamp (Before GPU) -> GPU (Device) -> Timestamp (After GPU) -> CPU for Image Window

Processing Time (ms) : Timestamp (After GPU) - Timestamp (Before GPU)


## Benchmark List

IS = Instace Segmentation <br>
SS = Semantic Segmentation

| Task | Model | FPS | Performance | Code |
|:---:|:---:|:---:|:---:|:---:|
| IS | yolact |  |  |  |
| IS | mask-rcnn |  |  |  |

