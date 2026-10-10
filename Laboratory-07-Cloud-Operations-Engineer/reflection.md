# Mission Reflection

Monitoring host resources is important even when containers are running properly because containers depend on the host machine's CPU, memory, and disk storage. If the host runs out of resources, applications inside containers may become slow or unavailable. Checking the system baseline helps engineers identify possible limitations before they affect users.

The `docker logs` command helps troubleshoot problems when a user cannot log in to a web application. By reviewing the logs, an engineer can look for recorded requests, error messages, and other events that may help explain the issue. These details help narrow down the possible cause and guide further investigation.

Logs and metrics provide different types of information. Logs record individual events, requests, and errors, while metrics provide numerical measurements such as CPU usage, memory consumption, and network activity. Using both helps engineers understand application behavior and resource performance.

Large enterprise companies can monitor thousands of containers by using centralized monitoring and visualization tools. Prometheus can collect and store metrics, while Grafana can display them in dashboards. These tools help teams observe many services, identify trends, and investigate performance problems more efficiently.

This laboratory activity improved my understanding of Linux troubleshooting and container monitoring. Commands such as `free -h`, `df -h /`, `top`, `docker logs`, and `docker stats` provide evidence about system health and application behavior. Testing both successful and unsuccessful HTTP requests also demonstrates how to check application responses. These skills are useful for identifying issues, documenting findings, and helping maintain reliable cloud services.
