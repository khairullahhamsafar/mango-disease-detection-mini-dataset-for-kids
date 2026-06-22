# Mango Disease Detection Mini Dataset for Kids

A small, kid-friendly mango leaf dataset designed for teaching machine learning, computer vision, and plant disease detection concepts to children.

This dataset helps students learn how AI can identify patterns in plant images and predict whether a mango leaf is healthy or diseased.

## 📁 Dataset Structure

```text
mango-disease-detection-mini-dataset-for-kids/
├── training/
│   ├── diseased/    # 15 training images
│   └── healthy/     # 15 training images
└── testing/
    ├── diseased/    # 2 testing images
    └── healthy/     # 2 testing images
```

### Classes

- `healthy`
- `diseased`

## 🎯 Purpose

This dataset is perfect for:

- Teaching machine learning to kids
- Introduction to computer vision
- Plant disease detection projects
- Agricultural AI demonstrations
- Image classification activities
- Learning about patterns and predictions
- STEM and AI education programs

## 📊 Details

| Attribute | Value |
|-----------|---------|
| Classes | 2 (healthy, diseased) |
| Training images per class | 15 |
| Total training images | 30 |
| Testing images per class | 2 |
| Total testing images | 4 |
| Total images | 34 |
| Dataset size | Mini/small |
| Source | Selected from a larger plant disease dataset |

## 🌱 Learning Objective

Using this dataset, students can:

1. Train a simple image classification model
2. Learn how AI detects patterns in plant leaves
3. Understand supervised machine learning
4. Explore how technology can help agriculture
5. Test model performance using unseen images
6. Learn the importance of training and testing data

## 🚀 Quick Start

```python
from pathlib import Path

dataset_dir = Path("mango-disease-detection-mini-dataset-for-kids")

for split in ["training", "testing"]:
    split_dir = dataset_dir / split
    print(f"\n{split.upper()}")

    for class_dir in split_dir.iterdir():
        if class_dir.is_dir():
            print(
                f"{class_dir.name}: "
                f"{len(list(class_dir.glob('*')))} images"
            )
```

## 🧪 Suggested Classroom Activity

1. Train a machine learning model using the images in the `training` folder.
2. Test the model using the images in the `testing` folder.
3. Compare predictions with the actual labels.
4. Discuss how the computer distinguishes healthy leaves from diseased leaves.

Questions for students:

- What visual differences can you see between healthy and diseased leaves?
- Which images were easiest for the model to classify?
- Why do we use separate training and testing datasets?
- How might adding more images improve predictions?

## ⚠️ Notes

- Images were selected and prepared from a larger publicly available plant disease dataset
- Intended for educational purposes and beginner AI/ML projects
- Designed for teaching image classification concepts
- Small size enables quick experimentation on local machines
- Suitable for classroom demonstrations and guided learning activities

## 📝 License

Public dataset for educational use.

## 🔍 Keywords

Machine Learning for Kids, AI for Kids, Computer Vision Dataset, Plant Disease Detection, Mango Disease Detection, Leaf Classification, Agricultural AI, Smart Farming, Image Classification Dataset, Educational Dataset, Beginner Machine Learning Dataset, Computer Vision for Beginners, Supervised Learning, Pattern Recognition, Prediction Models, STEM Education, Classroom AI Activities, Mini Dataset, Small Dataset, Mango Leaf Disease Detection

## 🏷️ Topics

#MachineLearning #ArtificialIntelligence #ComputerVision
#PlantDiseaseDetection #MangoDiseaseDetection
#ImageClassification #AgriculturalAI
#SmartFarming #AIForKids #MachineLearningForKids
#EducationalDataset #ComputerVisionDataset
#LeafClassification #SupervisedLearning
#PatternRecognition #STEMEducation
#DataScienceEducation #MiniDataset

## 👨‍💻 Author

Prepared and curated by **Khairullah Hamsafar** for educational and classroom learning purposes.

Focused on making Machine Learning, Artificial Intelligence, Computer Vision, Data Science, and Generative AI accessible to children, students, and beginners.
