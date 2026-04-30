<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>
<body>

  <h1>Explainable Gender-Aware Facial Emotion Detection via Hybrid Deep Learning and Customized Visual Dataset</h1>

  <p>A deep learning-based framework for joint Facial Emotion Recognition and Gender Classification is proposed using a convolutional neural network–based multi-task learning approach. Both tasks are learned simultaneously through shared feature representations, improving overall classification performance and enabling more robust and context-aware facial analysis.</p>

  <h2>Features</h2>
  <ul>
    <li>Emotion + Gender classification (12 classes)</li>
    <li>Object detection with bounding boxes</li>
    <li>Preprocessing: Grayscale, 640×640 resize, auto-orientation</li>
    <li>Dataset: 7,386 images, 11,253 annotations</li>
  </ul>

  <h2>Models Trained</h2>
  <ul>
    <li>YOLOv7</li>
    <li>YOLOv8</li>
    <li>YOLOv11</li>
    <li>YOLOv12</li>
    <li>RF-DETR</li>
    <li>XFDetNet (Best Performer)</li>
  </ul>

  <h2>Best Model Performance</h2>
  <ul>
    <li><strong>Precision:</strong> 96.1% </li>
    <li><strong>Recall:</strong> 99.2% </li>
    <li><strong>mAP@50:</strong> 99.5 </li>
  </ul>

   <h2>Ablation Study</h2>
  <p>Comprehensive experiments were conducted using <strong>YOLOv8</strong> and <strong>YOLOv11</strong> across <strong>five different controlled environments</strong> to evaluate the impact of preprocessing, augmentation, optimizer settings, and training strategies on facial emotion detection performance.</p>

  <h2>Dataset & Access</h2>
  <p>Source: Royalty-free images</p>
  <p>Public Dataset: <a href="https://zenodo.org/records/19675193" target="_blank">Zenodo</a></p>

  <h2>Tools Used</h2>
  <ul>
    <li>Roboflow (annotation)</li>
    <li>PyTorch, YOLO, Transformers</li>
  </ul>

  <h2>Usage</h2>
  <p>Clone the repo and follow model training scripts in the <code>/models</code> directory. Dataset folder structure: <code>train/</code>, <code>valid/</code>, <code>test/</code>.</p>

  <h2>Publication Status</h2>  
<p>The manuscript corresponding to this experiment has been submitted to the journal <i>The Visual Computer</i> (Springer Nature), with Manuscript ID: <code>c544c8e8-2291-4765-891c-ccd31ba1c1a9</code>.</p>

</body>
</html>
