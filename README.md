# Parquet Reader with Spring Boot & Elasticsearch

A Spring Boot application that reads data from Parquet files and sends it to Elasticsearch.

---

## 📦 Requirements

- Java 17+ or Java 21
- Maven 3.8+
- Elasticsearch installed and running locally (default port: 9200)
- Parquet files located at `../Parquet` relative to the project folder


## 🚀 How to Run the App
  ### 1. Clone the Repository

```bash
git clone https://github.com/Ahmedali3011/ParquetIngestor.git
cd ParquetIngestor

  ### 2.Place Parquet Files

/your-parent-folder
├── Parquet/          ← Put your `.parquet` files here
├── ParquetIngestor/   ← The Spring Boot project

  ### 3. Start Elasticsearch

If you don’t have Elasticsearch installed:

- [Download Elasticsearch](https://www.elastic.co/downloads/elasticsearch)
- Extract the archive
- Then run it:

```bash
cd elasticsearch-x.x.x
./bin/elasticsearch


  ### 4. Run the Spring Boot App
```bash
cd ParquetIngestor
./mvnw spring-boot:run
