Plant Disease Detection using MobileNetV2

This project applies **MobileNetV2**, a lightweight deep learning architecture, to detect plant diseases from leaf images.  
It is part of a comparative study where different CNN architectures (MobileNetV2, ResNet50, vgg16, InceptonV3, xception ) are evaluated for plant disease classification.

---

##  Dataset
- **Size:** 80,000+ images  
- **Classes:** 38 different plant diseases (including healthy leaves)  
- **Source:** Kaggle  

---

##  Model Details
- **Architecture:** MobileNetV2  
- **Input size:** 224x224 RGB images  
- **Optimizer:** Adam (lr=0.01)  
- **Loss Function:** Categorical Crossentropy  
- **Batch Size:** 32  
- **Epochs Trained:** 100  

---

##  Training Results
After training for **100 epochs**, MobileNetV2 achieved:

| Metric        | Training | Validation |
|---------------|----------|------------|
| Loss          | 0.0371   | 0.1154     |
| Accuracy      | 98.77%   | 96.98%     |

 The model shows **strong generalization** with high validation accuracy and low loss.

---

