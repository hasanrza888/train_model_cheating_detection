🎓 Exam Cheating Detection using Computer Vision

This repository contains the implementation files for the Master's thesis titled:
    "Application of Computer Vision in Smart Systems: A Case Study on Exam Cheating Detection"

📌 Overview
This project demonstrates the development of a smart system that detects cheating behavior in online exams using real-time computer vision techniques. The system integrates:
    YOLOv11 for object detection (student behavior classification),
    Head pose estimation to track direction of gaze,
    A custom-trained model based on annotated datasets,
    Video-based simulation testing for demonstration.

📁 Repository Structure

📦 Exam-Cheating-Detection
 ┣ 📂 demo_video/                 # Sample video used for simulation
 ┣ 📂 training_results/          # Training results (graphs, metrics, curves)
 ┣ 📂 model/                     # Final YOLOv11 trained weights (.pt)
 ┣ 📜 inference_demo.ipynb       # Notebook for demo testing with video
 ┣ 📜 training_notebook.ipynb    # Full notebook used to train the YOLOv11 model
 ┗ 📜 README.md                  # This file

📊 Key Results
    Precision: 0.596
    Recall: 0.732
    mAP@0.5: 0.735
    mAP@0.5:0.95: 0.492
    Fitness Score: 0.516

Evaluation was conducted on a 633-frame video where the model successfully detected cheating and accurately estimated head direction.

📸 Sample Output
A sample frame from the demo is included in the results, where:
    The student is correctly identified,
    The behavior is flagged,
    Head pose estimation overlays are visible.

🛠 Technologies Used
    Python 3.x
    Google Colab
    OpenCV
    Ultralytics YOLOv11
    Matplotlib
    MediaPipe (initially attempted for head pose)

📚 Related Academic Work
This project is part of the dissertation submitted to Azerbaijan State Oil and Industry University (ASOIU) under the supervision of Elviz Ismayilov.
It contributes to the research area of smart education systems, AI-based exam monitoring, and computer vision in IoT-enabled environments.

📄 License
This project is academic and research-based. Not intended for commercial use.
