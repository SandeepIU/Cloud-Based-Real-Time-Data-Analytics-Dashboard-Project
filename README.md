# Cloud-Based-Real-Time-Data-Analytics-Dashboard-Project

This project delivers a cloud-native, real-time analytics platform built on Microsoft Azure that processes high-velocity industrial data streams with sub-30-second latency. By leveraging cutting-edge serverless architecture and real-time processing capabilities, we bridge the gap between data generation and actionable insights.

****Core Components****


  *Data Ingestion:* Azure Event Hubs (handles high-volume sensor data)


  *Real-time Processing:* Azure Stream Analytics (SQL-based stream processing)


**Data Storage:**

fdf gdg
Azure Synapse Analytics (historical data warehouse)

Redis Cache (fast access to recent data)


  *Real-time Communication:* Azure SignalR Service (WebSocket connections)


  *Visualization:* React Dashboard (live data display)

**Key Features**


  *Real-time Processing:* < 30 seconds end-to-end latency


  *Scalable Architecture:* Handles 10,000+ events per second


  *Cloud-Native:* Fully serverless Azure services


  *Live Dashboard:* Real-time updates via WebSockets


  *Anomaly Detection:* Automatic pattern recognition in data streams


***Data Flow***

  *Ingest:* Sensor data **→** Event Hubs


  *Process:* Real-time analytics **→** Stream Analytics


  *Store:* Historical data **→** Synapse Analytics


  *Visualize:* Live updates **→** React Dashboard via SignalR

***Use Cases***


**Industrial Applications**


  * Predictive Maintenance* - Early detection of equipment failures


  * Production Monitoring* - Real-time factory operations tracking


  * Energy Management* - Power consumption optimization


  *Supply Chain Tracking* - Live logistics monitoring


  * Environmental Monitoring* - Safety and compliance tracking


**Dependencies**

*Backend* - 
azure-eventhub==5.11.2
azure-identity==1.15.0
aiohttp==3.9.1
python-dotenv==1.0.0

*Frontend* -
{
  "react": "^18.2.0",
  "typescript": "^4.9.0",
  "chart.js": "^4.4.0",
  "@microsoft/signalr": "^7.0.0"
}

***Azure Services***
  -Azure Event Hubs

  -Azure Stream Analytics

  -Azure Synapse Analytics

  -Azure SignalR Service

  -Azure App Service

  ***System Architecture***
  
<img width="561" height="201" alt="Azure Dashboard drawio" src="https://github.com/user-attachments/assets/df80dde6-e521-44c2-a583-eeb91ca46981" />
