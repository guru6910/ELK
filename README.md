# $${\color{red} \textbf{Elasticsearch Logstash Kibana}}$$

ELK stack is the powerfool toolset used for searching, analyzing, and visualizing log data in real time.

## $${\color{green} \textbf{🔍 1. Elasticsearch}}$$

A distributed search and analytics engine.

Stores data and enables fast full-text search, filtering, and aggregations.

Backend of the ELK Stack.

## $${\color{green} \textbf{📦 2. Logstash}}$$

A data processing pipeline.

Ingests data from multiple sources, transforms it, and then sends it to a destination (usually Elasticsearch).

Supports complex parsing, filtering, and enrichment of logs.

## $${\color{green} \textbf{📊 3. Kibana}}$$

A visualization and dashboard tool.

Interfaces directly with Elasticsearch to help you explore and visualize data.

Useful for creating dashboards, monitoring logs, or detecting anomalies.



# $${\color{purple} \textbf{🔄 Workflow Summary:}}$$

**Logstash** (or Beats) collects logs from your servers or applications.

Logs are processed and sent to **Elasticsearch**.

You use **Kibana** to visualize, search, and monitor the data.
