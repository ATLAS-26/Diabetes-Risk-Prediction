Problem Statement

Diabetes mellitus is one of the most prevalent chronic diseases worldwide, affecting over 463 million adults globally. Early detection and prevention are crucial, as undiagnosed or poorly managed diabetes can lead to severe complications including heart disease, kidney failure, blindness, and lower limb amputation.

This project aims to develop an accessible, AI-powered tool that can help individuals assess their diabetes risk using readily available health metrics. By leveraging machine learning, we can identify at-risk individuals earlier, enabling timely lifestyle interventions and medical consultations.

Methodology

Our machine learning approach

Model Selection We evaluated multiple classification algorithms including Logistic Regression, Random Forest, Gradient Boosting, and Neural Networks. The final model was selected based on a balance of accuracy, interpretability, and generalization capability.

Feature Engineering The model uses 8 key features: gender, age, hypertension status, heart disease status, smoking history, BMI, HbA1c level, and blood glucose level. These features were selected based on their clinical relevance and predictive power for diabetes.

Training & Validation The model was trained using stratified k-fold cross-validation to ensure robust performance across different data distributions. Hyperparameters were optimized using grid search with cross-validation.

Dataset Information

100,000+ Patient Records 8 Input Features ~91% Model Accuracy 0.89 ROC-AUC Score

The dataset includes anonymized health records with demographic information, medical history, and laboratory measurements. Data preprocessing included handling missing values, outlier detection, and feature normalization.

Technology Stack

Built with modern technologies

Next.js 16 React 19 TypeScript Tailwind CSS shadcn/ui Recharts Python/FastAPI scikit-learn

Project Goals & Outcomes

Develop an accurate and reliable diabetes risk prediction model Create an intuitive user interface for easy health metric input Provide interpretable AI explanations for predictions Enable what-if scenario simulations for health planning Offer educational content about diabetes prevention Demonstrate practical application of ML in healthcare

Limitations & Disclaimer

* This tool is for educational and informational purposes only • Predictions should not replace professional medical diagnosis • The model may not account for all diabetes risk factors • Results are probabilistic estimates, not definitive diagnoses • Always consult healthcare professionals for medical advice
