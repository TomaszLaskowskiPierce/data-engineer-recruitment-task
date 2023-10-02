# Data engineer recruitment task

## Task Objective
Your goal is to extract meaningful insights from attached dataset and present them in a visually appealing and easily understandable format. 
The visualizations you create should effectively communicate the key aspects of the data to Site Reliability Engineers (SREs).

These signals include latency, traffic, errors, and saturation. These metrics are considered fundamental for close monitoring in the realm of microservice applications. Specifically, this dataset provides an in-depth representation of these metrics for a frontend service.

## Metric Description
- Latency is represented by the metric **latency_mean** (measured in milliseconds)
- Traffic is denoted by the metrics ***request rate*** and ***ingress_request_rate*** (measured in requests per second)
- Errors are captured through the metric ***success_rate*** (it is a ratio of successfully processed requests to all requests and can vary from 0 to 100%)
- Saturation is reflected in the metrics ***cpu_usage*** (in millicores) and ***memory_usage*** (in bytes)
- Additionally, the dataset includes the metric ***tcp_connections_open*** which quantifies the number of active connections to the service, and ***ingress_reload*** which tracks the number of restarts of the ingress component responsible for routing traffic to the _frontend_ service.

Within the dataset, these aforementioned metric readings are recorded across 16 consecutive timestamps. These readings were collected during periods when various incidents occurred affecting the _frontend_ service, as well as during periods when the service was in a normal state (referred to as ***state normal***)

## Guidelines
Here are some detailed steps to guide you through this task:
- **Data Cleaning and Analysis**: Analyse the data using suitable statistical methods. Ensure any inconsistencies or outliers are addressed to maintain the integrity of your analysis.
- **Visualization:** Create clear and concise visualizations that highlight your findings. These could be in the form of graphs, charts, or any other visual representation that best suits the data. Remember, these visualizations should be easily interpretable by SREs.
- **Interpretation:** Draw meaningful conclusions from your analysis and visualizations. Explain what these findings mean in the context of the four golden signals and how they could potentially impact the performance of the frontend service.
- **Documentation:** Document your process, findings, and conclusions in a report. This report should be structured logically and written in a way that is easy for SREs to understand.

Remember, the goal here is not just to analyze the data, but to provide valuable insights that can help SREs monitor and improve the performance of their microservice applications. Good luck!


### Reference
[https://sre.google/sre-book/monitoring-distributed-systems/](https://sre.google/sre-book/monitoring-distributed-systems/ ) 



***Good luck***

__Co.Brick team__
