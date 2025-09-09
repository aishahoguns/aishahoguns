# Hello, I'm Aisha Ogunsola 👋

I'm a Machine Learning Engineer and Data Scientist with expertise in data analysis, predictive modeling, and AI-driven solutions. I specialize in uncovering actionable insights from complex datasets and translating them into impactful, data-driven strategies.  

With hands-on experience in Python, PyTorch, SQL, and machine learning, I’ve developed projects ranging from customer segmentation and predictive modeling to automated data mapping and deep learning pipelines. Recently, I gained practical experience through simulations with PwC, British Airways, and BCG, designing analytical solutions for real-world business challenges, including gender balance KPIs and customer churn predictions.  

Currently, I’m advancing my skills in predictive modeling, NLP, and healthcare data analytics, focusing on building scalable AI solutions. I enjoy solving complex problems, optimizing workflows, and delivering insights that enable smarter, data-driven decisions.  

📫 **How to reach me:** aishahoguns@gmail.com  

📄 [View my CV]([AISHA OGUNS.pdf](https://github.com/aishahoguns/aishahoguns/blob/main/AISHA%20OGUNS.pdf))  

---

## 🌟 Featured Project

### Automated Mapping of Clinical Equipment Categories  

**Code/Notebook:** [Automated_Equipment_Mapping.ipynb](https://github.com/aishahoguns/Automated_mapping_project)  

**Goal:** Develop an AI-driven system that maps unapproved clinical equipment names to standardized approved categories, improving data quality and operational efficiency in healthcare.  

**Description:**  
This project addressed the challenge of messy, unstructured clinical equipment data. Using synthetic dataset generation and NLP techniques, I created a model that automatically maps diverse equipment names (e.g., “INFUSION PUMP SYRINGE AMBULATORY”) to approved categories (e.g., “INFUSION PUMP,SYRINGE,AMBULATORY”). This automated solution significantly reduces manual work and ensures consistent, reliable data for analytics.  

**Skills:** Data cleaning, synthetic dataset generation, NLP, text preprocessing, classification, model evaluation  
**Technology:** Python, Pandas, NumPy, Scikit-learn, PyTorch, Jupyter Notebook  

**Results:**  
- Generated 3000+ synthetic examples to train the model  
- Achieved high accuracy in automated mapping  
- Streamlined equipment categorization, improving data reliability and reducing manual effort  

---

## 📊 Portfolio Projects  

### 1. Red Blood Cell Classification  

**Code/Notebook:** [RBC_Classification.ipynb](#)  

**Goal:** Build a hybrid deep learning and machine learning pipeline to classify individual red blood cells (RBCs) as circular, elongated, or other shapes from microscopic images.  

**Description:**  
This project implements an end-to-end pipeline combining semantic segmentation, deep learning feature extraction, and traditional ML classification:  
- **Data Loading & Preprocessing:** Images loaded from Google Drive with augmentation and normalization applied  
- **Segmentation:** U-Net++ used to isolate cells; multiple encoders (ResNet34, ResNet50, EfficientNet-b3, MobileNetV2) and thresholds explored  
- **Feature Extraction:** Embeddings from pretrained CNNs (ResNet-50, VGG-16, DenseNet121, Inception-v3, MobileNetV2) with classification heads removed  
- **ML Classification:** Features fed into SVM, Logistic Regression, Random Forest, Naive Bayes, and Decision Tree classifiers  
- **Evaluation:** Accuracy, classification reports, confusion matrices, and visualizations compared performance  

**Key Findings:**  
- DenseNet121 + Logistic Regression/SVM achieved the highest accuracy  
- Naive Bayes and Decision Tree performed consistently worse  
- Pipeline demonstrates the power of combining semantic segmentation + CNN feature extraction + ML classifiers for RBC classification  

**Technology & Tools:** Python, PyTorch, OpenCV, Scikit-learn, NumPy, Pandas, Jupyter Notebook  

---

### 2. Analyzing Customer Purchasing Behavior in the Chips Category  

**Code/Notebook:** [Customer_Purchasing_Behavior_Analysis.ipynb](https://github.com/aishahoguns/Portfolio_Projects/tree/main/Customer_purchasing_behaviour)  

**Goal:** Identify key drivers of chip sales, segment customers by purchasing behavior, and provide actionable recommendations to optimize sales and engagement.  

**Description:**  
Analyzed transactional and customer data from a supermarket’s chip category. Tasks included data cleaning, EDA, customer segmentation, statistical testing, and visualization to uncover patterns in purchasing behavior.  

**Skills:** Data cleaning, EDA, customer segmentation, statistical analysis (t-tests, chi-square), visualization  
**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, SciPy  

**Results:**  
- Identified older families and young singles/couples as top contributors to sales  
- “Mainstream” young singles/couples were 21% more likely to purchase Tyrrells chips  
- Recommended increasing visibility of premium brands near discretionary spaces to boost impulse buying
