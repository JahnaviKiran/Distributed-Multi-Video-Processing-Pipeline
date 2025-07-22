# Distributed Multi-video processing pipeline with Python and Confluent Kafka

Stream and process multiple videos in near real time using Kafka. The video frames are processed and a machine learning model does inference on them and the results are stored in a mongodb database.

- Designed and deployed a distributed pipeline to ingest video streams and classify frames using ResNet50
- Persisted frame data and metadata in MongoDB with fault-tolerant, scalable architecture for efficient storage
- Tuned Kafka producer configurations and utilized a 3-partition topic to boost reliability, parallelism, and high-throughput bulk insert performance.


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
