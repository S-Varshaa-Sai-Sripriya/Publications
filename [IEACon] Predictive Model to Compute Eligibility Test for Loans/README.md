Title: 💳 Loan Eligibility Predictor with ANN & Business Constraints (CIBIL, eSign, Salary Threshold)

Citation:
> S. V. S. Sripriya, S. D. S. Varrey, & M. Venkateshkumar. (2022). *Predictive Model to Compute Eligibility Test for Loans*. IEEE Industrial Electronics and Applications Conference (IEACon), pp. 185–190. [DOI: 10.1109/IEACon55029.2022.9951727](https://ieeexplore.ieee.org/document/9951727)


Description:
This repository contains an end-to-end ML solution that automates loan eligibility checks for banks using a rule-augmented AI model integrating financial and behavioral heuristics.
🔍 Key Features:

    Problem Addressed: Eligibility filtering for loan applications using real-world financial metrics and compliance conditions (CIBIL, income, e-sign, etc.).

    Data Handling:

        Dataset with 100 entries — refined to 23 eligible candidates post filtering

        Applied filtering on:

            CIBIL score ≥ 700

            e-Sign flag = True

            Balance after 1.25% interest ≥ ₹5000/year

    Models Compared:

        Artificial Neural Network (ANN) with ReLU + sigmoid

        Random Forest, SVM, XGBoost, Gradient Descent

        ANN achieved 100% accuracy on refined data

    Feature Engineering:

        Dummy variable encoding (pay schedule, collateral type)

        Risk score normalization, income brackets, custom thresholds

    Metrics & Interpretation:

        Binary Cross Entropy loss, accuracy, balance check logic

        Business rule implementation prior to ML inference

🧠 Novelty & Impact:

    Integrates hard business rules + ML for effective eligibility filtration

    Demonstrates how AI can automate regulatory-compliant banking workflows

    Optimizes banker time by reducing false approvals using layered decision filters

    Highlights real-world applicability of ANN in financial use cases
