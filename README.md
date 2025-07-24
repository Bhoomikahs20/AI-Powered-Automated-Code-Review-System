# 🤖 AI-Powered Automated Code Review System

This project builds an automated AI-driven code review pipeline using transformer models like CodeBERT, GraphCodeBERT, and CodeT5.

## 💡 Features
- **Bug Detection**: Classifies code as 'Buggy' or 'Fixed'
- **Severity Classification**: Categorizes issues into Critical, Major, Minor, and Warning
- **Code Suggestions**: Identifies bad practices and suggests improvements
- **Comment Generation**: Explains review results in natural language (optional)
- **Trust & Explainability**: (Planned) Use attention rollout and token attribution to visualize model decisions

## 🧠 Models Used
- [CodeBERT](https://huggingface.co/microsoft/codebert-base)
- [GraphCodeBERT](https://huggingface.co/microsoft/graphcodebert-base)
- [CodeT5](https://huggingface.co/Salesforce/codet5-base)

## 📚 Datasets
- GitHub Code Snippets
- CodeXGLUE (bug detection, fix)
- Google Code Review Comments
- Custom annotated dataset for severity classification

## ⚙️ Tools & Stack
- Python, Transformers (HuggingFace)
- PyTorch / TensorFlow
- Google Colab
- Pandas, NumPy
- FastAPI (for deployment)
- MongoDB (storage layer)

## 📂 Project Structure
- `model_inference.py` – loads model and performs bug/severity classification
- `notebooks/` – includes training logs, dataset cleaning, and analysis
- `data/` – training and evaluation data
- `results/` – contains metrics like F1, accuracy, CodeBLEU

## 📈 Metrics
- Accuracy, Precision, Recall, F1
- CodeBLEU, BLEU (for comment/fix generation)

---

© Bhoomika H S | Final Year AI Student | 2025 Graduate
