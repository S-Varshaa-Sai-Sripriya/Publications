Title: 🩻 PneumoNet: Multi-Class Pneumonia Diagnosis from Chest X-Rays with Custom VGG16 CNN

Citation:
> P. S., S. V. Sai Sripriya, A. R. Lalitha Pranathi, & M. Muthulakshmi. (2022). *Diagnosis of Acute Respiratory Syndromes from X-Rays using Customised CNN Architecture*. IEEE International Conference on Artificial Intelligence in Engineering and Technology (IICAIET), pp. 1–5. [DOI: 10.1109/IICAIET55139.2022.9936750](https://ieeexplore.ieee.org/document/9936750)

Description:
This repository presents a multi-class image classification model to diagnose acute respiratory syndromes (viral, fungal, bacterial) from chest X-ray images. The model is built upon a custom VGG16-based CNN architecture optimized for medical diagnostics.
🔍 Key Features:

    Objective: Early detection of COVID-19 and other pneumonia types via chest X-ray image classification

    Dataset: Collected 3-class X-ray dataset (Viral, Fungal, Bacterial), resized & preprocessed for uniformity

    Model:

        Customized VGG16 CNN using:

            ReLU + LeakyReLU

            Dropout regularization (0.5 and 0.3)

            Categorical Cross-Entropy

            Trained for 50 epochs with batch size of 50

        Achieved:

            Train Accuracy: 97.87%

            Test Accuracy: 90.00%

            Best class-level sensitivity for bacterial/fungal pneumonia

    Visualization & Evaluation:

        Training curves, confusion matrix, sensitivity & specificity metrics

        SMOTE used in prior works referenced for dataset balancing

    Infrastructure: Google Colab, TensorFlow, Python

🧠 Novelty & Impact:

    Performs multi-class medical image diagnosis, beyond binary (COVID/Non-COVID) classification

    Tailors VGG16 for domain-specific classification via custom head layers

    Achieves state-of-the-art accuracy compared to 10+ prior methods

    Potentially deployable in resource-limited clinical settings
