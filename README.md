# VRV Security

## Overview
VRV Security is a comprehensive security management system designed to analyze and detect suspicious activities from server log files. This project focuses on efficient log file parsing, detecting anomalies, and providing insights into system usage.

---

## Features
- **Request Analysis**: Counts the number of requests per IP address.
- **Endpoint Monitoring**: Identifies the most frequently accessed endpoint.
- **Suspicious Activity Detection**: Detects IPs with excessive failed login attempts.
- **Results Export**: Saves analysis results to a CSV file.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - `csv` for result export.
  - `collections.Counter` for data aggregation.
  - `typing` for type hints.

---

## Installation

### Clone the Repository
```bash
git clone https://github.com/yvishwas40/VRV-Security.git
cd VRV-Security
