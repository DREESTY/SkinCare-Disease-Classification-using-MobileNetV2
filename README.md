This project focuses on building a deep learning model to classify different skin conditions and diseases using transfer learning with MobileNetV2. The dataset consists of categorized images of common dermatological conditions such as acne, eczema, carcinoma, wrinkles, and more.

The workflow includes:

Data Loading & Preprocessing: Using image_dataset_from_directory with organized train/val/test folders.

Transfer Learning: Leveraging MobileNetV2 pretrained on ImageNet for efficient feature extraction.

Fine-tuning: Adjusting the top layers and applying data augmentation for generalization.

Class Imbalance Handling: Computing class weights dynamically from dataset distribution.

Optimization: Implementing callbacks like ReduceLROnPlateau, ModelCheckpoint, and EarlyStopping to improve performance.

Evaluation Metrics: Accuracy, Top-3 Accuracy, and confusion matrix visualizations to assess classification performance.

The final model achieves around 78% accuracy, and further improvement can be achieved with higher resolution inputs, stronger augmentations, and fine-tuning deeper layers of MobileNetV2.
