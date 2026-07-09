# SuperDiver

SLAM & Computer Vision Engineer

8 years of experience in computer vision algorithm development and product
delivery, with a focus on SLAM, multi-view geometry, RGB-D vision, industrial
inspection, and embedded optimization.

## Current Focus

- RGB-D SLAM and online 3D reconstruction
- Multi-view geometry and camera pose processing
- 3D Gaussian Splatting
- Industrial computer vision and model deployment

## Selected Projects

### [ORB2GS](https://github.com/SuperDiver/ORB2GS)

An online RGB-D Gaussian mapping prototype that connects ORB-SLAM3 tracking
with a PyTorch and gsplat mapping backend through ZeroMQ.

- Publishes RGB-D keyframes, camera poses, and sparse map points from a
  headless ORB-SLAM3 pipeline.
- Performs Gaussian initialization, incremental optimization, replay,
  visibility filtering, capacity control, and runtime monitoring.
- Runs end to end on the TUM RGB-D `freiburg1/desk` sequence with live viser
  visualization.

### [PCB Defect Detector](https://github.com/SuperDiver/pcb-defect-detector)

A YOLOv8s-based detector for six common PCB surface defect categories, covering
model training, evaluation, export, benchmarking, and an interactive demo.

- Precision `0.977`, recall `0.987`, mAP50 `0.990`, and mAP50-95 `0.573` on
  2,616 validation images.
- PyTorch and ONNX Runtime end-to-end latency of `15.3 ms` and `14.0 ms` on an
  RTX 4060 Laptop GPU.

## Engineering Background

- Delivered computer vision algorithms for robotic vacuum SLAM, smart
  projectors, driver monitoring, ADAS research, and industrial inspection.
- Experienced in algorithm feasibility analysis, implementation, embedded
  optimization, validation, production support, and cross-team collaboration.

## Technology

`C++` `Python` `OpenCV` `PyTorch` `ORB-SLAM3` `Multi-view Geometry` `RGB-D`
`ZeroMQ` `gsplat` `YOLOv8` `ONNX Runtime` `DSP/SIMD`
