# -IoT-Blockchain-Security-Analysis

This project explores the intersection of IoT (Internet of Things) and blockchain technology for securing connected devices against cyber threats. Using a real-world IoT dataset, the analysis evaluates how effectively blockchain can mitigate different types of security attacks while also tracking performance indicators like processing time and energy consumption.

📁 Dataset Overview

The dataset includes detailed logs of IoT device interactions and potential threats. 

Key fields:

Device ID

IoT Layer

Request Type

Data Size (KB)

Processing Time (ms)

Security Threat Type

Attack Severity (0-10)

Blockchain Transaction Time (ms)

Consensus Mechanism

Energy Consumption (mJ)

Threat Mitigated (1 = Yes, 0 = No)

📊 Key Analyses

Threat Landscape Overview – Identifies the most common security threats in IoT networks.

Threat Mitigation Effectiveness – Pie chart shows 71.7% of threats were mitigated, 28.3% were not.

Attack Severity by Threat Type – Box plot reveals which threats are most severe.

Processing Time vs Data Size – Scatter plot visualizes how larger data leads to longer processing.

Consensus Mechanism Analysis – Compares blockchain transaction time and energy use by consensus type.

Energy Consumption Distribution – Identifies outliers in power usage across IoT requests.

Threat Type vs Data Size – Looks for patterns between attack type and data volume.

IoT Layer vs Threat Count – Highlights which IoT layers are more vulnerable.

Correlation Heatmap – Shows relationships between numerical features like severity, time, and energy.

Summary KPIs – Includes total requests, average severity, and overall mitigation rate.

🧠 Insights

DDoS and spoofing are the most frequent threats.

Blockchain mitigates over 70% of threats, but gaps remain in spoofing and tampering.

PoS and PBFT consensus mechanisms are more energy-efficient than PoW.

Higher data sizes and severity scores lead to longer processing times.

✅ Recommendations

Prioritize high-severity threats in real-time processing strategies.

Use lightweight consensus mechanisms for IoT edge devices.

Optimize energy use in high-severity threat handling.

Strengthen mitigation for underperforming threat categories.

📌 Tools Used

Python (Pandas, Matplotlib, Seaborn)

Jupyter Notebook

📁 How to Use

Clone this repo and open IoT_Blockchain_Security_Analysis.ipynb in Jupyter Notebook. The notebook includes both the visual analysis and explanatory markdowns.
