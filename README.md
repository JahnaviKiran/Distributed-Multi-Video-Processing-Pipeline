# Distributed Multi-video Processing Pipeline

- Architected and deployed a distributed pipeline for video ingestion and frame classification using ResNet50.

- Implemented scalable, fault-tolerant storage of frame data and metadata in MongoDB.

- Optimized Kafka producers and leveraged a 3-partition topic to enhance reliability, parallelism, and high-throughput bulk inserts.

- Streamed and processed multiple videos in near real-time using Kafka, performing frame-level inference with a machine learning model and storing results in MongoDB.

# --- Install Dependencies ---
```
pip install -r requirements.txt
```
# --- Run the Application ---
Before Running, you have to start MongoDB and Kafka Server Instance.

# --- Run Producer Application ---
```
python producer_app.py
```
# --- Run Consumer Application ---
```
python consumer_app.py
```
