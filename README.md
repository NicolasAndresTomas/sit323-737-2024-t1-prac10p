## Monitoring and Visibility 

1. Dockerfile:
   - Created a Dockerfile to containerize the Node.js application

2. Docker Compose:
   - Configured services for the Node.js app, Prometheus, and Grafana
   - Set up networking and volumes for containerized services

3. Build and Run Containers:
   - Built and ran the Docker containers using docker-compose up -d

4. Prometheus Configuration:
   - Created prometheus.yml to configure Prometheus to scrape metrics

5. Add Prometheus as a Data Source in Grafana:
   - Accessed Grafana at http://localhost:3001
   - Added Prometheus at http://prometheus:9090 as a data source

6. Add Prometheus as a Data Source in Grafana:
   - Created dashboard in Grafana to visualize metrics 
