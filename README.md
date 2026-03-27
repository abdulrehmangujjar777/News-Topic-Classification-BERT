# News Topic Classification using BERT Fine-Tuning

## 📌 Project Overview
This project involves fine-tuning the **BERT-base-uncased** transformer model to classify news articles into four categories: **World, Sports, Business, and Sci/Tech**. This task was completed as part of my AI/ML Engineering Internship at Developers Hub Corporation.

## 🛠️ Technical Workflow
The project follows a state-of-the-art NLP pipeline:
1. **Dataset:** Used the `AG News` dataset via Hugging Face `datasets` library.
2. **Preprocessing:** Implemented `AutoTokenizer` for subword tokenization, handling padding, and truncation for BERT's 512-token limit.
3. **Model:** Fine-tuned `AutoModelForSequenceClassification` with a custom classification head.
4. **Trainer API:** Utilized the Hugging Face `Trainer` API for optimized training, including:
   - Dynamic evaluation during training.
   - Learning rate scheduling and weight decay.
5. **Optimization:** Achieved high accuracy by leveraging transfer learning from pre-trained BERT weights.

## 📊 Key Results
- **Transformer Power:** Demonstrated the ability to handle complex context in text compared to traditional NLP models.
- **Evaluation:** Monitored accuracy and loss metrics throughout the training epoch.
- **Deployment Ready:** The model and tokenizer are saved in a reusable format for real-time inference.

## 📁 Project Structure
- `Task 3 BERT MOdel .ipynb`: Complete Jupyter Notebook with code and outputs.
- `my_news_model/`: Directory containing the fine-tuned model weights.
- `README.md`: Project documentation.

## 🚀 Technologies Used
- **Language:** Python
- **Libraries:** Transformers, Datasets, PyTorch, Evaluate, Accelerate
- **Model:** BERT (Bidirectional Encoder Representations from Transformers)
