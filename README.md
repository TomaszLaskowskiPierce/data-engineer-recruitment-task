# Data engineer recruitment task

The dataset provided pertains to Google’s site reliability engineers (SREs) and their definition of four crucial metrics for monitoring microservice applications, referred to as the ***four golden signals*** 
These signals encompass latency, traffic, errors, and saturation and are regarded as the fundamental set of metrics deserving close monitoring. 
The dataset specifically offers an expanded representation of these metrics for the _frontend_ service.

## Metric Description
- Latency is represented by the metric **latency_mean** (measured in milliseconds)
- Traffic is denoted by the metrics ***request rate*** and ***ingress_request_rate*** (measured in requests per second)
- Errors are captured through the metric ***success_rate*** (it is a ratio of successfully processed requests to all requests and can vary from 0 to 100%)
- Saturation is reflected in the metrics ***cpu_usage*** (in millicores) and ***memory_usage*** (in bytes)
- Additionally, the dataset includes the metric ***tcp_connections_open*** which quantifies the number of active connections to the service, and ***ingress_reload*** which tracks the number of restarts of the ingress component responsible for routing traffic to the _frontend_ service.

Within the dataset, these aforementioned metric readings are recorded across 16 consecutive timestamps. These readings were collected during periods when various incidents occurred affecting the _frontend_ service, as well as during periods when the service was in a normal state (referred to as ***state normal***)

## Requirements
Using the attached dataset analyze the data and visualize the most important aspects using your preferred method.

### Reference
[https://sre.google/sre-book/monitoring-distributed-systems/](https://sre.google/sre-book/monitoring-distributed-systems/ ) 



***Good luck***

__Co.Brick team__
