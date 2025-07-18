# Tomato-Plant-Growth-Prediction
🍅Tomato Plant Growth Prediction Using YOLOv9 for IoT System Integration

📌 Overview
This project leverages YOLOv9 to predict the growth stage of tomato plants, classifying them into five distinct stages. The predictions are then integrated into an IoT-based smart greenhouse system that autonomously adjusts environmental conditions based on the identified stage.
This project leverages YOLOv9 to detect the growth stage of tomato plants, classifying them into the following five distinct stages:

1-Seed Germnation Stage
2-Seedling Stage 
3-Vegetative Stage 
4-Flowering Stage 
5-Fruiting_Ripening Stage –


🎯 Objective
To build an intelligent agriculture system that:

Detects the current growth stage of tomato plants in real-time.

Adjusts greenhouse parameters like temperature, humidity, lighting, and irrigation accordingly.

Minimizes human intervention and enhances overall plant health and yield.

🧠 Model: YOLOv9
Model Type: Object Detection

Architecture: YOLOv9

Target Output: One of 5 tomato growth stages

Why YOLOv9? Fast and accurate real-time detection, suitable for edge/IoT deployment.

🖼️ Dataset
Stage 1 & 2: Captured directly from a real tomato farm.

Stage 3-5: Collected from publicly available image datasets and agricultural sources.

Preprocessing:

Image resizing & normalization

Annotated using [Roboflow / LabelImg / other tool]

🧪 System Workflow
Camera Capture
Real-time image capture from greenhouse cameras.

Prediction (YOLOv9)
Image is passed to the YOLOv9 model to detect the current plant growth stage.

IoT Integration
Based on the predicted stage, the IoT system:

Controls lighting intensity

Regulates temperature & humidity

Manages irrigation timing

Automation & Optimization
Ensures optimal growing conditions with minimal human input.

🌿 Key Benefits
✅ Improved crop health and yield

✅ Reduced resource consumption (water, energy)

✅ Real-time monitoring and decision-making

✅ Scalable to other crops and environments
