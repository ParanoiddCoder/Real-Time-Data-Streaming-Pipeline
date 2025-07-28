# Real-Time Yelp Data Streaming & Sentiment Analysis Pipeline  

A real-time data processing pipeline that streams Yelp reviews, performs sentiment analysis, and visualizes results using Kafka, Spark, MongoDB, HuggingFace, Elasticsearch, and Kibana.  

The pipeline consists of:  
1. **Kafka Producer** (Python/Kaggle Notebook): Streams Yelp data from CSV.  
2. **Apache Spark Structured Streaming**: Processes/transforms data in real-time.  
3. **MongoDB Atlas**: Intermediate storage for processed data.  
4. **Confluent Kafka**: Manages data ingestion & stream processing.  
5. **HuggingFace Model** (DistilBERT): Performs sentiment analysis on reviews.  
6. **Elasticsearch**: Indexes data for search/analytics.  
7. **Kibana**: Real-time dashboards for visualization.  

---

## Technologies Used
* **Python**: Core language for building the Kafka producer, Spark streaming jobs, and data processing scripts.
* **Apache Kafka (Confluent Cloud)**: Manages real-time data ingestion and message brokering between services.
* **Apache Spark (Structured Streaming)**: Performs real-time stream processing and transformation on incoming data.
* **MongoDB Atlas**: Serves as temporary storage for raw or intermediate streaming data.
* **HuggingFace Transformers**: Applies pre-trained NLP models for sentiment analysis on incoming reviews.
* **Elasticsearch**: Stores and indexes enriched data for fast search and retrieval.
* **Kibana**: Visualizes Elasticsearch data through interactive dashboards and charts.

---




