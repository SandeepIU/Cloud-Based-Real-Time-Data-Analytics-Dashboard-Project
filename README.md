# Cloud-Based-Real-Time-Data-Analytics-Dashboard-Project

****Core Components****


*Data Ingestion:* Azure Event Hubs (handles high-volume sensor data)


*Real-time Processing:* Azure Stream Analytics (SQL-based stream processing)


**Data Storage:**


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


**Data Flow**

*Ingest:* Sensor data **→** Event Hubs


*Process:* Real-time analytics **→** Stream Analytics


*Store:* Historical data **→** Synapse Analytics


*Visualize:* Live updates **→** React Dashboard via SignalR

