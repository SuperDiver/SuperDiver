# Xiaotian Fu

**SLAM / Computer Vision Algorithm Engineer**

[中文](./README.md)

## Contents

- [Professional Profile](#professional-profile)
- [Capability Profile](#capability-profile)
- [Technical Progression](#technical-progression)
- [Working Methods and Engineering Value](#working-methods-and-engineering-value)
- [Recent Public Projects](#recent-public-projects)

## Professional Profile

I have eight years of experience in computer vision algorithm development and engineering. My long-term foundation includes classical computer vision, machine learning, algorithm innovation, embedded optimization, and product engineering. My technical path has progressed from traditional 2D vision to 2D/3D algorithms for smart projectors and then to 3D SLAM systems. I am currently deepening my work in VSLAM and online 3D mapping through ORB-SLAM3.

My most notable professional results are in smart projector algorithms. As an early pioneer and core developer in this field, I created new product capabilities with object detection and multi-view geometry, and carried them through algorithm design, engineering implementation, quality management, optimization, mass production, and multiple product iterations under real-world constraints.

In SLAM, I have engineering experience with the complete workflow and quality assurance of Cartographer-based LiDAR-inertial SLAM. I am now extending that foundation through source-level ORB-SLAM3 work focused on VSLAM workflows and 3D mapping. Machine learning was used throughout my earlier projects, while my deep learning experience is concentrated in research prototypes, solution validation, and recent public projects.

**Current focus:** [ORB2GS - VSLAM and online 3D mapping](https://github.com/SuperDiver/ORB2GS) | [PCB Defect Detector - deep learning detection capability](https://github.com/SuperDiver/pcb-defect-detector)

## Capability Profile

### Long-Term Depth

- **Algorithm innovation and productization:** Start from the problem itself and its physical constraints, design an algorithmic solution, and carry it through implementation, testing, optimization, mass production, and continued iteration.
- **Classical vision and machine learning:** Long-term use of feature, geometry, segmentation, detection, clustering, classification, and temporal methods, including OpenCV, HOG/SVM, DBSCAN, Kalman filtering, and hidden Markov models.
- **Embedded systems and performance:** Algorithm migration, SIMD optimization, and runtime evaluation on platforms including NXP S32V and DSPs.
- **Process quality management:** Continued practice in development-process control, automated validation, anomaly analysis, and feedback loops across smart projector, SLAM, and recent public projects.

### SLAM Experience and Current Direction

- **Cartographer LiDAR-inertial SLAM:** Familiar with the overall workflow, major modules, and related core computation. My concrete results focused on release engineering, quality systems, map-result analysis, and acceleration of selected computation.
- **ORB-SLAM3 / VSLAM:** Progressed from framework usage to source modifications, key-workflow analysis, and end-to-end integration. I am familiar with the tracking, keyframe, pose, map-point, and local-mapping data flow of feature-based VSLAM, which is now my primary area of deeper study.
- **3D vision:** Connecting RGB-D data, coordinate transforms, point clouds, and 3D Gaussian Splatting to explore how SLAM localization can support online 3D mapping.

## Technical Progression

### 2016.08 - 2018.02 | Independent ADAS Algorithm Research and Embedded Validation

**BYD Auto Industry Co., Ltd. · 15th Business Unit | Algorithm Engineer**

- Spent approximately one year independently researching ADAS capabilities on the NXP S32V platform, covering investigation, solution design, implementation, and performance validation for LDW and PCW prototypes.
- Built an original algorithm framework combining feature extraction, Kalman filtering, LSD/Hough line detection, DBSCAN, and LeNet-5, and evaluated embedded runtime performance with SIMD optimization.
- Participated in decoupling a 360-degree surround-view algorithm from its legacy platform and analyzing the target platform for migration.

> **Capability developed:** Established the ability to independently research complex algorithms, combine multiple technical approaches, and evaluate them on embedded hardware. Because this was confidential pre-research, public information focuses on methods and engineering implementation.

---

### 2018.03 - 2020.04 | Extending 2D Perception, Multi-Sensor Vision, and System Solution Design

**Shenzhen Tengshi Technology Co., Ltd. | Algorithm Engineer**

- Served as a primary developer for nine near-infrared driver-monitoring functions, including smoking, phone use, fatigue, eyewear, and seat-belt detection, covering feasibility analysis, data preparation, algorithm implementation, DSP migration, testing, and maintenance.
- Combined HOG/SVM, connected-component analysis, hidden Markov models, and near-infrared image processing. I later extended the system with an Orbbec structured-light sensor and independently designed an RGB-D segmentation algorithm.
- Demonstrated the product at the 20th China Hi-Tech Fair, contributing to subsequent cooperation with Orbbec, and filed four patents.

> **Product result:** Multiple functions were deployed and shipped. In 2019, four functions in the company's product became the first in China to pass the relevant tests under Ministry of Transport Document No. 115.

**Hefei Taihe Optoelectronic Technology Co., Ltd. · Beijing Branch | Senior Algorithm Engineer**

- Evaluated stereo vision for AGV forklift tine positioning, including algorithm implementation and accuracy/performance assessment.
- Worked on visible/thermal dual-spectrum monitoring, underground coal-rock recognition, and industrial monitoring projects, covering field investigation, hardware selection and engineering solution design, deep learning solution design, algorithm prototyping, and effect validation.

---

### 2020.06 - 2022.03 | Pioneering Smart Projector Algorithms and Building 2D/3D Product Depth

**JMGO · Shenzhen Holatek Co., Ltd. | Senior Image Algorithm Engineer**

- Led feasibility analysis, algorithm design, implementation, testing, quality control, and mass-production support for automatic screen fitting, adaptive image placement, intelligent image flattening, digital zoom, and ambient-light adaptation.
- Applied fundamental geometry, multi-view geometry, and object-detection methods to model the relationship between the projected image and the physical environment, continuously addressing accuracy, stability, environmental robustness, and product constraints.
- Built the vision algorithm laboratory and participated in the engineering design of an automated test system and its algorithmic effect-evaluation pipeline. Filed 14 patents, eight of which were granted during my tenure.

> **Industry impact:** As an early pioneer and core developer of smart projector algorithms, I helped bring these capabilities into mass production with the JMGO J10, establishing a new smart projector product category roughly six months ahead of the industry. Core function performance metrics ranked first in the industry.

> **Technical originality:** As of June 2026, intelligent image flattening remains the only mass-produced capability of its kind in the industry, creating more than five years of sustained product differentiation.

---

### 2022.09 - 2023.11 | SLAM System Engineering and Quality Assurance

**Anker Innovations · Eufy | SLAM Algorithm Engineer**

- Supported robotic-vacuum development and release based on Cartographer LiDAR-inertial SLAM, becoming familiar with the overall sensor-input, major-module, map-result, and release workflow.
- Independently built two dedicated systems: a SLAM release self-test system and an automated user-map anomaly detection system for regression testing and batch map-quality analysis.
- Completed a small hardware-acceleration project for selected SLAM computation and became familiar with the relevant algorithms. My work focused on system engineering, quality assurance, and computation optimization.
- Supported the Nebula projector team during a concentration of production issues, quickly building a system-level view, driving diagnosis and debugging, and helping maintain normal production across the product line.

> **Team value:** Added critical engineering and quality capabilities to the SLAM team through self-testing, map anomaly analysis, and computation acceleration, while providing cross-team troubleshooting and delivery assurance for the Nebula team.

---

### 2024 - Present | Independent System Development and Focused VSLAM Expansion

- Led a personal knowledge-management product from concept to core implementation, covering requirements, architecture, technology selection, frontend/backend development, and an Agent workflow based on LLMs, knowledge graphs, ReAct, and LangGraph.
- Continued the progression from 2D vision to projector 2D/3D algorithms and then to 3D SLAM systems, with current study and hands-on work centered on feature-based VSLAM through ORB-SLAM3.

---

## Working Methods and Engineering Value

### Continuous Innovation

- **Algorithm-level innovation:** Self-developed connected-component algorithms, lane-detection operators, and an analytical solution for the maximum inscribed rectangle of an arbitrary convex quadrilateral under multiple constraints, among other work.
- **System and solution innovation:** Independently designed an ADAS framework, developed an RGB-D segmentation solution, pioneered smart projector product functions, created the intelligent image-flattening algorithm, built SLAM quality tools, and connected ORB-SLAM3 with a Gaussian mapping pipeline, among other work.
- **Results:** Filed 18 patents across my career; at least eight were granted during my tenure.

### Process Quality Management

I received formal training in process quality management and progressively formed, validated, and refined this methodology in real product development.

- **Smart projector stage:** Across two iterations of functions such as automatic screen fitting and intelligent image flattening, I participated in product definition, feasibility analysis, algorithm design, effect evaluation, quality control, and mass-production support. I also built the vision algorithm laboratory and contributed to the automated test system and effect-evaluation algorithms, providing a quality foundation for industry-leading metrics and stable deployment across later product lines.
- **SLAM stage:** I independently built the SLAM release self-test system and user-map anomaly detection system, converting parts of regression testing and map-quality inspection into repeatable, batch-executable engineering workflows and improving pre-release validation and issue discovery.
- **Recent projects:** ORB2GS includes module tests, explicit ZMQ protocol constraints, runtime monitoring, and end-to-end validation. The PCB project preserves training, validation, and inference benchmark results so that conclusions can be reproduced from code and data.

These practices shaped my view of process quality: algorithm quality depends not only on final output, but also on clear objectives, reliable evaluation, observable development processes, diagnosable failures, reproducible results, and sustained delivery.

### Technical Backstop and Delivery Assurance

Providing a technical backstop requires stepping beyond assigned boundaries to rapidly understand the system, identify critical risks, fill missing tooling, coordinate relevant people, and drive issues to closure. At Anker, I supplemented engineering and quality capabilities through dedicated systems and supported cross-team diagnosis during Nebula production incidents, helping maintain normal production. This capability is grounded in technical breadth, system-level judgment, process-quality awareness, and ownership of outcomes.

## Recent Public Projects

### [ORB2GS: ORB-SLAM3 + 3D Gaussian Online Mapping](https://github.com/SuperDiver/ORB2GS)

**Positioning: a primary capability demonstration for VSLAM and 3D mapping.**

- Built an online Gaussian mapping prototype for RGB-D scenes, connecting ORB-SLAM3 localization with a 3D Gaussian Splatting mapping pipeline.
- Modified key ORB-SLAM3 workflows, including Tracking and Local Mapping, to publish images, depth, poses, and map points. The Python side implements keyframe pairing, RGB-D back-projection, Gaussian initialization, incremental training, replay, frustum filtering, and capacity control.
- Completed end-to-end validation on the TUM RGB-D `freiburg1/desk` sequence, including ORB-SLAM3 tracking, online data transfer, incremental Gaussian scene growth, model snapshots, and viser runtime visualization.

### [PCB Defect Detector: Detection and Inference Evaluation](https://github.com/SuperDiver/pcb-defect-detector)

**Positioning: a capability demonstration for deep learning detection and a complete project workflow.**

- Trained and evaluated YOLOv8s for six PCB defect categories, exported PyTorch/ONNX models, benchmarked inference, and built a Gradio demo.
- Trained on 10,710 images. On 2,616 validation images with 5,436 instances, the model achieved precision `0.977`, recall `0.987`, mAP50 `0.990`, and mAP50-95 `0.573`.
- On an RTX 4060 Laptop GPU, end-to-end PyTorch/ONNX latency was `15.3/14.0 ms`.