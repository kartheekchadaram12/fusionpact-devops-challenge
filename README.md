Full Stack Deployment, Monitoring, and CI/CD Automation
Project Overview
Deployed a full-stack application (frontend + backend) on a single AWS server, implemented observability using Prometheus, Grafana, Node Exporter, and automated deplyment with Jenkin CI/CD pipeline.

1. Full Stack Deployment
Steps Taken:
    1. Cloned repository: fusionpact-devops-challenge.
    2. Built Docker images for backend and frontend:
        ◦ backend → Python 3.10 application.
        ◦ frontend → Nginx serving HTML.
    3. Verified Docker images:
       docker images
    4. Ran containers using docker run:
        ◦ Backend exposed on port 8000.
        ◦ Frontend exposed on port 80.
    5. Confirmed application is accessible on public IP.
    6. Captured screenshots for SOP.

2. Monitoring & Observability
Tools Installed:
    • Prometheus – Scraping backend and node metrics.
    • Node Exporter – Installed on server for system metrics.
    • Grafana – Dashboards for application and infrastructure metrics.
Steps Taken:
    1. Installed Prometheus, Node Exporter, and Grafana on the server.
    2. Configured Prometheus to scrape:
        ◦ localhost:9090 (Prometheus metrics)
        ◦ localhost:9100 (Node Exporter metrics)
    3. Created Prometheus service and started it.
    4. Created Node Exporter service and started it.
    5. Installed Grafana and started Grafana service.
    6. Connected Grafana to Prometheus as data source.
    7. Created dashboards for:
        ◦ Infrastructure Metrics: CPU, Memory, Disk, Container usage.
        ◦ Application Metrics: Request rate, latency, error counts.
    8. Verified real-time data collection.
    9. Captured screenshots for SOP.

3. CI/CD Automation
Steps Taken:
    1. Installed Jenkins on the server.
    2. Created a Jenkins pipeline (Jenkinsfile) with stages:
        ◦ Code checkout from GitHub.
        ◦ Build Docker images for frontend and backend.
        ◦ Stop existing containers.
        ◦ Run new containers.
    3. Executed the pipeline successfully.
    4. Verified frontend and backend after deployment.
    5. Documented pipeline execution screenshots.

4. Verification & Evidence
    • Application accessible via public IP:
        ◦ Frontend: http://<public-ip>
        ◦ Backend: http://<public-ip>:8000
    • Prometheus showing metrics: verified.
    • Grafana dashboards showing real-time metrics.
    • CI/CD pipeline logs in Jenkins: verified successful builds and deployment
      SOP: Full Stack Deployment, Monitoring, and CI/CD Automation
Project Overview
Deployed a full-stack application (frontend + backend) on a single AWS server, implemented observability using Prometheus, Grafana, Node Exporter, and automated deployment with Jenkins CI/CD pipeline.

1. Full Stack Deployment
Steps Taken:
    1. Cloned repository: fusionpact-devops-challenge.
    2. Built Docker images for backend and frontend:
        ◦ backend → Python 3.10 application.
        ◦ frontend → Nginx serving HTML.
    3. Verified Docker images:
       docker images
    4. Ran containers using docker run:
        ◦ Backend exposed on port 8000.
        ◦ Frontend exposed on port 80.
    5. Confirmed application is accessible on public IP.
    6. Captured screenshots for SOP.

2. Monitoring & Observability
Tools Installed:
    • Prometheus – Scraping backend and node metrics.
    • Node Exporter – Installed on server for system metrics.
    • Grafana – Dashboards for application and infrastructure metrics.
Steps Taken:
    1. Installed Prometheus, Node Exporter, and Grafana on the server.
    2. Configured Prometheus to scrape:
        ◦ localhost:9090 (Prometheus metrics)
        ◦ localhost:9100 (Node Exporter metrics)
    3. Created Prometheus service and started it.
    4. Created Node Exporter service and started it.
    5. Installed Grafana and started Grafana service.
    6. Connected Grafana to Prometheus as data source.
    7. Created dashboards for:
        ◦ Infrastructure Metrics: CPU, Memory, Disk, Container usage.
        ◦ Application Metrics: Request rate, latency, error counts.
    8. Verified real-time data collection.
    9. Captured screenshots for SOP.

3. CI/CD Automation
Steps Taken:
    1. Installed Jenkins on the server.
    2. Created a Jenkins pipeline (Jenkinsfile) with stages:
        ◦ Code checkout from GitHub.
        ◦ Build Docker images for frontend and backend.
        ◦ Stop existing containers.
        ◦ Run new containers.
    3. Executed the pipeline successfully.
    4. Verified frontend and backend after deployment.
    5. Documented pipeline execution screenshots.

4. Verification & Evidence
    • Application accessible via public IP:
        ◦ Frontend: http://<public-ip>
        ◦ Backend: http://<public-ip>:8000
    • Prometheus showing metrics: verified.
    • Grafana dashboards showing real-time metrics.
      
    • CI/CD pipeline logs in Jenkins: verified successful builds and deployment


<img width="1306" height="714" alt="Screenshot from 2025-10-15 10-49-59" src="https://github.com/user-attachments/assets/f9cacb91-95fa-41bd-a71b-8fb61e5991a6" />

<img width="1306" height="714" alt="Screenshot from 2025-10-15 11-02-31" src="https://github.com/user-attachments/assets/07c02ccc-925d-4b1e-ac89-bffa6a08559b" />

<img width="1306" height="714" alt="Screenshot from 2025-10-15 12-03-57" src="https://github.com/user-attachments/assets/0538f799-f81a-4321-a2e0-ed1c81caf741" />

<img width="1306" height="714" alt="Screenshot from 2025-10-15 12-36-12" src="https://github.com/user-attachments/assets/60fce9f3-3923-4cd3-bfd2-5d8999f4f461" />

<img width="1306" height="714" alt="Screenshot from 2025-10-15 13-04-41" src="https://github.com/user-attachments/assets/a46e54af-49c1-449f-a02f-b873a602bc6a" />

<img width="1306" height="714" alt="Screenshot from 2025-10-15 12-37-22" src="https://github.com/user-attachments/assets/061565a6-e61d-4a3d-ade6-76af39cb746a" />
