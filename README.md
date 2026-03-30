🌱 PEST DETECTION AND MITIGATION:
AI-based computer vision system for real-time agricultural pest detection using lightweight YOLO models. This project helps farmers identify pests early and take timely action to reduce crop loss.

🚀 Features:
•🔍 Real-time pest detection using deep learning
•⚡ Lightweight models (YOLOv5-Nano, YOLOv8-Nano, YOLOv11-Nano)
•📦 Bounding boxes with labels & confidence scores
•🌾 Trained on IP102 dataset
•🔄 Strong data augmentation for better field performance
•📱 Suitable for edge devices / low-power systems

🧠 Models Used:
•YOLOv5-Nano
•YOLOv8-Nano
•YOLOv11-Nano
These models are optimized for speed + accuracy trade-off, making them ideal for real-time agricultural applications.

📊 Dataset:
📁 IP102 Dataset
•Contains 100+ pest classes
•Real-world agricultural images

🛠️ Tech Stack:
Python 🐍
OpenCV
PyTorch
Ultralytics YOLO
NumPy / Pandas

📂 Project Structure:
Bash
├── data/               # Dataset files
├── models/             # Trained weights
├── notebooks/          # Training & experiments
├── src/
│   ├── detect.py       # Inference script
│   ├── train.py        # Training pipeline
│   └── utils.py
├── results/            # Output images/videos
├── requirements.txt
└── README.md

⚙️ Installation;?:
Bash
git clone https://github.com/your-username/pest-detection.git
cd pest-detection
pip install -r requirements.txt

▶️ Usage:
🔹 Run Detection
Bash
python src/detect.py --source image.jpg --weights models/best.pt
🔹 Train Model
Bash
python src/train.py --data data.yaml --epochs 50

📸 Output:
Bounding boxes around pests
Class label (e.g., aphid, beetle, etc.)
Confidence score
Example:
Pest: Aphid | Confidence: 92%

🎯 Applications;
•Smart farming systems 🌾
•Precision agriculture
•Early pest detection
•Crop monitoring automation

🔮 Future Enhancements:3
•📱 Mobile app integration
•🌐 IoT-based real-time monitoring
•🧪 Pest severity analysis
•🤖 Automated pesticide recommendation system

🤝 Contributing:
Contributions are welcome! Feel free to fork the repo and submit pull requests.

📜 License:
This project is licensed under the MIT License.

👨‍💻 Author:
Harininivatha
AI & Data Science Student

⭐ Support:
If you like this project, give it a ⭐ on GitHub!