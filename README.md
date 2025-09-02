# Fish_Image_Classification
This project focuses on classifying different types of fish and seafood using deep learning models. It explores both custom CNNs and pretrained architectures like VGG16, ResNet50, MobileNet, InceptionV3, and EfficientNetB0 to compare performance.


📌 Project Overview

Implemented data preprocessing & augmentation using PyTorch.

Trained multiple transfer learning models (VGG16, ResNet50, MobileNet, InceptionV3, EfficientNetB0).

Built a custom CNN from scratch for baseline comparison.

Evaluated models using accuracy, loss curves, and confusion matrices.

Deployed a Streamlit web app for real-time predictions.

📂 Dataset

The dataset contains 11 classes of fish and seafood:

animal fish

animal fish bass

black sea sprat

gilt head bream

horse mackerel

red mullet

red sea bream

sea bass

shrimp

striped red mullet

trout

(You can mention dataset source if public, e.g., Kaggle)

⚙️ Models Used

Custom CNN – Simple baseline model.

VGG16 – Deep CNN with 16 layers.

ResNet50 – Residual connections to handle vanishing gradients.

MobileNet – Lightweight model for mobile/edge devices.

InceptionV3 – Multi-scale feature extraction.

EfficientNetB0 – Balanced accuracy & efficiency via compound scaling.

📊 Results & Insights

ResNet50 & EfficientNetB0 performed best with high accuracy.

MobileNet was fastest and lightest, good for deployment.

Custom CNN gave lower accuracy but served as a learning baseline.

Training history plots (accuracy & loss) and confusion matrices were used to evaluate performance.

🚀 Streamlit App

The app allows:

Uploading a fish image.

Selecting a pretrained model (VGG16, ResNet50, MobileNet, InceptionV3, EfficientNetB0).

Getting predicted fish category with confidence scores.
