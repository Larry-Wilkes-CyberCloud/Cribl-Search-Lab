# 🎯 Cribl Search Essentials & Architecture Lab

A hands-on implementation and validation project demonstrating distributed log analysis at rest using **Cribl Search**. This lab focuses on querying unstructured telemetry data directly in cloud object storage and distributed edge nodes without pre-indexing costs or storage bloat.

---

## 🏆 Proof of Completion: Lab Check Passed

Below is the verification of successful task completion for the Cribl Search lab scenario. This scenario required using Cribl Search to investigate a multi-stage security incident, from initial attack vector to data exfiltration.

<p align="center">
  <img width="662" height="591" alt="image_0" src="https://github.com/user-attachments/assets/ff6aa053-62ac-45fd-9102-16a5c2f79db1" />
</p>


## 🛠️ Key Technical Capabilities Demonstrated

* **Data Exploration at Rest:** Configured search targets across cloud object storage (Amazon S3) and local file paths to query raw logs in place.
* **Search Pipeline Optimization:** Authored custom Search expressions using pipeline operators to filter, project, and aggregate high-volume datasets efficiently.
* **Dynamic Field Extraction:** Applied Regular Expressions (Regex) and runtime parsing logic to extract key audit fields on-the-fly, reducing search latency during incident response.
* **Telemetry Routing Integration:** Integrated Cribl Search workflows with Cribl Stream/Edge to filter high-value security events for downstream analysis.

---

## 📐 Architecture & Workflow

1. **Target Configuration:** Pointed Cribl Search at raw log destinations (Amazon S3 bucket / local data streams).
2. **Dataset Definition:** Defined search datasets with precise path matchers and event breakers.
3. **Query Execution:** Executed targeted search queries using pipeline transformations (`where`, `extract`, `summarize`).
4. **Data Reduction:** Filtered out telemetry noise to yield actionable threat intelligence and system metrics.

---

## 🚀 Impact & Key Takeaways

By querying log data directly at the edge or in low-cost storage, teams eliminate unnecessary ingestion costs and indexing overhead while maintaining immediate visibility for threat hunting and compliance auditing.



