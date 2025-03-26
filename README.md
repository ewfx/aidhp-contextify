# 🚀 AI-Driven Hyper-Personalization & Recommendations

## 📌 Table of Contents
- [Introduction](#-introduction)
- [Demo](#-demo)
- [Inspiration](#-inspiration)
- [What It Does](#-what-it-does)
- [How We Built It](#-how-we-built-it)
- [Challenges We Faced](#-challenges-we-faced)
- [How to Run](#-how-to-run)
- [Tech Stack](#-tech-stack)
- [Team](#-team)

---

## 🎯 Introduction
The project is about: The Cold Start phase occurs when new customers have just opened their accounts but have no transaction or product purchase history. In this phase, the project will leverage a popularity-based model to recommend the most popular, top-selling products to these customers.

## 🎥 Demo
📹 Video : https://github.com/ewfx/aidhp-contextify/blob/main/artifacts/Screen-Recording2.mp4  
🖼️ Screenshots:

![Screenshot 1](link-to-image)
![n8n workflow](/artifacts/arch/architecture.jpg)

## 💡 Inspiration
The inspiration to create a project on AI-Driven Hyper-Personalization & Recommendations in banking stems from several key factors:

- Increased Competition in the Financial Sector
- Data-Driven Insights
- Improved Customer Retention
- Maximizing Revenue Opportunities
- Efficient Marketing and Product Delivery

## ⚙️ What It Does
The GBDT + LR (Gradient Boosting Decision Tree + Logistic Regression) recommender is a hybrid model that integrates the strengths of both gradient boosting decision trees and logistic regression. It utilizes the powerful feature-learning capabilities of gradient boosting decision trees along with the interpretability and flexibility of logistic regression.

This method takes advantage of both models: the GBDT component captures complex patterns and interactions, while the LR component enhances interpretability and efficiently handles feature engineering. As a result, this hybrid approach often leads to improved recommendation performance and is capable of managing large-scale datasets with high-dimensional features.

In the context of recommendation systems, once the GBDT + LR model is trained, it can be used to generate personalized product recommendations for customers. Given a customer's profile, item features, and user-item interactions, the model predicts the likelihood of user-item preferences. The items with the highest predicted probabilities are then recommended to the customer.

1. **Implementation:**  
   Once the recommendation model is developed and initially tested using validation data, it is essential to evaluate its performance using real examples from the subsequent period. This helps ensure that the model is both accurate and reliable by applying appropriate evaluation metrics and validation techniques.
   Next, the model should be integrated into the bank's current infrastructure (e.g., CRM, mobile app, website accounts) to ensure seamless data transfer via APIs. It is also crucial to implement A/B testing to compare the effectiveness of your recommendation model against alternative approaches. This process enables continuous refinement and optimization based on user feedback and business objectives.
   Given the highly regulated nature of the banking industry, it is also imperative that the system complies with all relevant privacy regulations. Adequate safeguards should be put in place to protect customer data before the model is deployed.


2. **Improvement:**  
   This project represents a simplified version of a real-world product recommendation system in the banking sector. Several areas can be improved in future work:
    - **Feature Selection and Engineering:** Currently, the project relies only on customer features and purchasing behavior. Including additional product characteristics such as product category, customer segment, term, risk level, profitability, and variance would significantly enhance the accuracy and relevance of the recommendations.
    - **Training and Testing Datasets:** In real-world scenarios, using a larger, more diverse set of training data would provide a more comprehensive understanding of customer behavior and population characteristics. Additionally, leveraging advanced infrastructure (e.g., cloud storage and computing resources) would expedite and improve the model training process.
    - **Recommendation Methods:** While the models used in this project are well-established and effective in the industry, there are more advanced deep learning models, such as YouTubeDNN and DeepFM, that can uncover more complex patterns in the data and generate more precise recommendations. Furthermore, employing a hybrid model-one that combines multiple recommendation algorithms could further enhance the predictive power of the system.

## 🛠️ How We Built It
- Python, JupyterNote, Decision Tree

## 🚧 Challenges We Faced
- Designing a scalable architecture because of limited DataSet

## 🏃 How to Run
1. Clone the repository
   ```sh
   git clone https://github.com/ewfx/aidhp-contextify.git
   ```
2. Install dependencies
   ```sh
   pip install -r requirements.txt (for Python)
   ```
3. Run the project
   ```sh
   start  # or python app.py
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: TKinter
- 🔹 Backend: Python
- 🔹 Database: CSV

## 👥 Team
- **Srinivasa Reddy Angaluri**
- **Rishabh Sharma** - [GitHub](https://github.com/rishabhstar) | [LinkedIn](#)
- **Karthik Vanka** - [GitHub](https://github.com/buddykartz) | [LinkedIn](#)
- **Kuldeep Kumar** - [GitHub](https://github.com/chaudharyklbsimds) | [LinkedIn](#)
- **Harsimran Singh** - [GitHub](https://github.com/ricks21) | [LinkedIn](#)