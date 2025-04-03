# 🧠 Top-Startup-Founders

**AI-driven prediction and profiling of top scientists for startup success.**

This project leverages machine learning and natural language processing to analyze over 1,000 top scientists' **publications**, **patents**, and **grant histories**, aiming to identify researchers with high potential for **startup success**. By combining state-of-the-art embedding models and ensemble learning, we generate actionable insights to support **investment** and **product development** decisions.

---

## 🚀 Key Highlights

- 🔍 Extracted key features from large-scale researcher datasets using advanced NLP and transformer-based embeddings (e.g., `allenai-specter`)
- 🧪 Trained and fine-tuned ML models: **Neural Network**, **XGBoost**, **Decision Trees**, and more
- 🧠 Built an **ensemble majority voting classifier**, achieving ~**90% accuracy** in predicting startup outcomes
- 📊 Delivered interpretable outputs for **investors**, **VCs**, and **startup founders** to identify high-impact scientific talent

---

## 🗂️ Project Structure

### 📁 `prediction.ipynb`
Processes researcher metadata and textual content (publications, patents, grants). Core tasks:
- Sentence embedding using `allenai-specter`
- Feature engineering across multiple institutions
- Model training (classification and similarity scoring)

### 📁 `correlation_0.ipynb`
Analyzes cross-institutional patterns and correlation in scientist success predictors, validating generalizability of the models across universities.

### 📄 `sample`
Example input/output file (can be replaced with your data). Format typically includes researcher name, affiliation, text fields (abstracts/patents), and labeled outcomes.

---

## 📦 Installation

```bash
pip install pandas matplotlib numpy transformers keyphrasetransformer sentence-transformers scikit-learn xgboost
```

---

## 🧠 Models Used

| Model Type         | Purpose                                 |
|--------------------|-----------------------------------------|
| `allenai-specter`  | Generate semantic embeddings from text  |
| `XGBoost`          | Feature-rich startup success prediction |
| `Neural Network`   | Deep modeling of researcher profiles    |
| `Decision Trees`   | Transparent classification models       |
| `VotingClassifier` | Ensemble method (~90% accuracy)         |

---

## 💼 Use Cases

- 💰 **VC & Investment Strategy** – Prioritize researchers with strong innovation potential
- 🚀 **Startup Partnerships** – Identify academic collaborators with commercial success prospects
- 🔬 **R&D Analytics** – Track emerging research trends and their entrepreneurial applications

---

## 📍 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Top-scientist-for-Startups.git
   cd Top-scientist-for-Startups
   ```

2. Run notebooks:
   - Use `prediction.ipynb` to generate features and train predictive models
   - Use `correlation_0.ipynb` for analysis across institutions

3. Modify `sample` or replace with your dataset (`.csv`) following the expected schema.

---

## 📈 Sample Output

- Similarity scores between scientists and startup keywords
- Top predicted scientists ranked by success probability
- Confusion matrix, classification report (accuracy, precision, recall)

---

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

If you have any questions or suggestions, feel free to reach out or open an issue.

---

Let me know if you want this saved as a `README.md` file, or if you'd like to include badges (like GitHub stars, last updated, license, etc.)!
