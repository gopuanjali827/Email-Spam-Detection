# Email-Spam-Detection

Spam emails (also known as junk mail) are unsolicited messages sent to a large number of users, often containing **advertisements, scams, phishing links, or fraudulent offers**. Since they can be harmful or simply waste users’ time, detecting and filtering spam is an important real-world problem.

In this project, we build a **machine learning model using Python** that can automatically classify emails into **Spam (1)** or **Not Spam (0)**.

We use **text preprocessing, feature extraction (TF-IDF), and a classification algorithm (Naive Bayes)** to train the model. Once trained, the model can take any email message as input and predict whether it is spam or not.

---

## ⚙️ Workflow

1. **Import Libraries**
   Load required Python libraries such as Pandas, NumPy, Scikit-learn.

2. **Load Dataset**
   Use the dataset (spam.csv) which contains emails labeled as **ham (not spam)** or **spam**.

3. **Data Preprocessing**

   * Remove unnecessary columns.
   * Encode labels (ham → 0, spam → 1).

4. **Text Vectorization**
   Convert text into numerical features using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

5. **Model Training**
   Use **Multinomial Naive Bayes**, a popular algorithm for text classification.

6. **Model Evaluation**
   Measure performance using **Accuracy, Confusion Matrix, and Classification Report (Precision, Recall, F1-score)**.

7. **Prediction on New Emails**
   Allow users to input a custom email text and predict whether it is **Spam** or **Not Spam**.

---

## 📊 Expected Output

* **Accuracy**: Usually between **95% – 98%** depending on dataset.
* **Confusion Matrix & Classification Report**: Shows how well the model separates spam vs non-spam.
* **Custom Predictions**:

  * `"Congratulations! You won $1000..." → Spam`
  * `"Hi John, let’s meet tomorrow..." → Not Spam`

---

## 🚀 Applications

* Automatically filter spam emails in inbox.
* Detect phishing or scam attempts.
* Improve security and user experience in email services.

