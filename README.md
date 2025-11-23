Airflow Installation

1. Open a terminal and run this command
```bash
curl -LfO 'https://airflow.apache.org/docs/apache-airflow/3.1.3/docker-compose.yaml'
```
2. Setup the .env 
```bash
AIRFLOW_UID=50000
```
3. Build the Docker
```bash
docker compose -f docker-compose.yaml up --build
```
4. Run the Docker
```bash
docker compose -f docker-compose.yaml up -d
```