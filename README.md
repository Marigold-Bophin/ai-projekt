<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# SkinAI: AI-powered Skin Disease Diagnosis

Final project for the Building AI course

## Summary

SkinAI is an AI-powered system that predicts and classifies skin diseases based on image analysis. By utilizing deep learning and medical image databases, it helps dermatologists and general practitioners in early diagnosis, potentially preventing serious conditions like melanoma.

## Background

Skin diseases affect millions worldwide, ranging from mild conditions like eczema to life-threatening melanoma. Early detection is crucial for successful treatment, but access to dermatologists is often limited.

* Millions of people suffer from undiagnosed or misdiagnosed skin conditions.
* Many cases of melanoma and other serious diseases could be prevented with early detection.
* There is a global shortage of dermatologists, leading to long wait times for patients.

As someone interested in AI applications in healthcare, I see this project as an opportunity to improve medical diagnostics and accessibility to early skin disease detection.

## How is it used?

Patients, general practitioners, or dermatologists can upload a photo of a skin lesion or affected area. The AI model analyzes the image and provides a classification along with recommendations.

1. The user uploads an image of the affected skin area.
2. The AI model processes the image using deep learning.
3. The system predicts the condition (e.g., eczema, psoriasis, melanoma).
4. The user receives a risk assessment and a recommendation to consult a specialist if necessary.

### Example:

<img src="https://upload.wikimedia.org/wikipedia/commons/8/85/Melanoma.jpg" width="400">

## Data sources and AI methods

Data is collected from:
* Open medical image databases such as [ISIC Archive](https://www.isic-archive.com/).
* Publicly available dermatological research papers.
* Synthetic data generation to improve AI training.

Methods:
* **Deep Learning** – Convolutional Neural Networks (CNN) for image classification.
* **Transfer Learning** – Using pre-trained models like ResNet and EfficientNet.
* **Data Augmentation** – Increasing dataset diversity for better accuracy.

| AI Method       | Use Case |
| -------------- | --------------------- |
| CNNs | Skin disease classification |
| Transfer Learning | Improving accuracy with pre-trained models |
| Data Augmentation | Enhancing model robustness |

## Challenges

* Accuracy depends on the quality and diversity of the dataset.
* AI cannot replace medical professionals—only assist them.
* Ethical concerns regarding the collection and use of medical images.
* Bias in datasets (limited representation of different skin tones).

## What next?

* Integration into mobile applications for real-time skin analysis.
* Expansion of the dataset with more diverse skin types and conditions.
* Collaboration with dermatologists to improve model performance.
* Regulatory approval to ensure safety and reliability for medical use.

## Acknowledgments

* Inspired by AI applications in medical diagnostics.
* Data sourced from ISIC Archive and other open medical datasets.
* Example AI-driven diagnostic tools: [SkinVision](https://www.skinvision.com/), [Dermoscopy AI](https://www.dermoscopy.ai/).
