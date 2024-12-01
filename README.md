# Vietnamese Fake News Detection in Real-Time


## Overview
This project, *Vietnamese Fake News Detection on Social Networks*, tackles the growing issue of misinformation on social media in Vietnam. Leveraging advanced machine learning, deep learning, and big data technologies, our system identifies fake news in real time to curb its spread and minimize societal harm.

---

## Key Features
- **Real-Time Detection**: Processes data streams using Apache Kafka and PySpark for immediate results.
- **Multimodal Analysis**: Combines text-based features with social context for comprehensive fake news detection.
- **Online Learning**: Continuously updates the model with new data for improved accuracy over time.
- **Big Data Frameworks**: Utilizes scalable tools like Apache Kafka and Spark for handling large-scale data efficiently.

---

## Technologies Used
- **Programming Languages**: Python (PySpark, TensorFlow, PyTorch)
- **Big Data Frameworks**: Apache Kafka, Apache Spark
- Machine Learning, Deep Learning, Pretrained Models

---

## Dataset
1. **ReINTEL Dataset**: 5,172 labeled records from Vietnamese social networks.
2. **Custom Dataset**: 2,500 records collected from reputable and unreliable sources, labeled as real or fake.

**Highlights:**
- Over 7,600 combined records for training and testing.
- Metadata simplification for focused analysis.

---

## Methodology
1. **Data Preprocessing**:
   - Remove unnecessary data (e.g., emails, HTML tags, redundant characters).
   - Perform word segmentation using VnCoreNLP.
2. **Feature Extraction**:
   - Use TF-IDF for traditional models.
   - Leverage FastText embeddings for deep learning models.
3. **Model Training**:
   - Traditional Models: Logistic Regression, Decision Tree, SVM, etc.
   - Deep Learning Models: BiLSTM, Text CNN, and their hybrid.
4. **System Architecture**:
   - Stream data using Apache Kafka.
   - Preprocess and predict using Spark Streaming with integrated models.
5. **Online Learning**:
   - Incremental updates with new data for enhanced performance.

---

## Results
- **Traditional Models**: Achieved up to 91.25% accuracy with ensemble techniques.
- **Deep Learning Models**: Combined Text CNN + BiLSTM achieved a top accuracy of 91.4%.
- **Real-Time System**: Efficiently identifies fake news with high performance on live data streams.

---

## Future Work
- Incorporate monolingual models optimized for Vietnamese.
- Expand dataset with diverse and up-to-date records.
- Enhance model performance with hyperparameter tuning.

---

## Acknowledgments
- ReINTEL 2020 for the dataset.
- Open-source contributions to Apache Kafka and PySpark.
- Research on Vietnamese language processing using PhoBERT.
