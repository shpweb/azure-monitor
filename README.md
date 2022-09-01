# azure-monitor
- Azure Monitor helps you maximize the availability and performance of your applications and services.  
- It delivers a comprehensive solution for **collecting, analyzing, and acting on telemetry** from your cloud and on-premises environments. 
- This information helps you understand how your applications are performing and proactively identify issues that affect them and the resources they depend on.


#### A few examples of what you can do with Azure Monitor include:

- **Applicaiton Insights:** Detect and diagnose issues across applications and dependencies
- **VM insights and Container insights:** Correlate infrastructure issues
- **Log Analytics:** Drill into your monitoring data for troubleshooting and deep diagnostics.
- **Automated Actions:**  Support operations at scale
- **Azure Dashboard & Workbooks:** Create visualizations
- **Azure Monitor Metrics:** Collect data from **monitored resources**
- **Change Analysis:** Investigate change data for routine monitoring or for triaging incidents by using Change Analysis.

## Overview
- The following diagram gives a high-level view of Azure Monitor. 
- At the center of the diagram are the data stores for **metrics and logs**, which are the two fundamental types of data used by Azure Monitor. 
- On the left are the **sources of monitoring data** that populate these **data stores.** 
- On the right are the different functions that Azure Monitor performs with this collected data. This includes such actions as **analysis, alerting, and streaming to external systems.**


![image](https://user-images.githubusercontent.com/92606493/187622799-4812057e-c119-47df-89d0-021f3216016d.png)


**Insights:** Service-specific monitoring features built into Azure Monitor.

### Metrics:
- Short, time-based data
- Frequently updated
- Near real-time data
- Alerts based on numeric values
- Visualization via Metrics Explorer

### Logs:
- Long, event-based data
- Sporadically updated
- Free-form and/or structured
- Stored in Log Analytics Workspace
- Built-in query language (Kusto)
