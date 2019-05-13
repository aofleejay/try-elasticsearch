# Try Elasticsearch
:books: Repository for practice about elasticsearch.

## 🚀 Quick start
-  **Start elasticsearch**
    ```
    docker-compose up
    ```

-  **Create sample index**
    ```
    curl -H "Content-Type: application/json" -XPOST "localhost:9200/bank/_bulk?pretty&refresh" --data-binary "@accounts.json"
    ```

-  **List all indices**
    ```
    curl "localhost:9200/_cat/indices?v"
    ```