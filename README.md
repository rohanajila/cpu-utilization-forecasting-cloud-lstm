# Cloud-Based Time Series Prediction of CPU Load Using Deep Learning

## 📘 Overview
This research project presents a cloud-native solution for forecasting CPU utilization in Microsoft Azure virtual machines using historical time-series data. The system is built using AWS services (EC2, Cloud9, S3) and implements advanced deep learning models like LSTM, BiLSTM, and a novel Multihead BiLSTM for accurate predictions.

## 🧠 Research Question
How can cloud-based machine learning and deep learning models effectively forecast CPU utilization, and why is this critical for optimizing resource allocation in dynamic cloud environments?

## 🚀 Features
- Data preprocessing & feature extraction using Python
- Rolling window-based time series transformation
- Model training with Decision Tree, Gradient Boosting, LSTM, BiLSTM, Multihead BiLSTM
- Performance metrics: RMSE, R² Score
- Cloud deployment using AWS Cloud9, EC2, and S3

## 🔧 Technologies Used
- Python 3.9
- AWS Cloud9, EC2, S3
- TensorFlow, Keras, Scikit-learn
- Pandas, NumPy, Plotly, Seaborn
- Jupyter Notebook

## 🧪 Results
| Model                | RMSE   | R² Score |
|---------------------|--------|----------|
| Decision Tree        | 0.0480 | 0.866    |
| Gradient Boosting    | 0.0321 | 0.940    |
| LSTM                 | 0.0331 | 0.936    |
| BiLSTM               | 0.0246 | 0.965    |
| **Multihead BiLSTM** | **0.0213** | **0.974** |

> 🔥 **Multihead BiLSTM outperformed all models**, offering the most accurate forecast.

## 📂 Project Structure
- `report/`: Final project report, configuration manual, presentation slides
- `src/notebooks/`: Python notebooks used for data processing and modeling
- `dataset/`: Preprocessed Azure time-series data (if public)

## 🎓 Author
**Rohan Ajila**  
MSc Cloud Computing  
National College of Ireland  
Student ID: 22249729  

## 📄 Related Documents
- [📄 Final Research Report](./report/MSc%20Research%20Project%20Report.pdf)
- [🛠️ Configuration Manual](./report/Configuration%20Manual.pdf)
- [📊 Presentation Slides](./report/Presentation%20Slides.pptx)

## 🛠️ Future Enhancements
- Real-time data streaming with AWS Kinesis
- GPU-based model training
- CI/CD pipeline for automated model retraining
- Memory & Network forecasting alongside CPU

## 📃 License
None

