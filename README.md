# chaosLogMonitor 🔥

**chaosLogMonitor** is a cross-platform terminal tool built to **monitor, analyze, and detect suspicious IP addresses** from access logs based on request frequency. Designed with cybersecurity in mind, this tool helps identify potential brute-force, DDoS, or scanning activity by filtering IPs crossing a defined threshold.

---

## 🚀 Features

- ⚡ Detects suspicious IPs from access logs
- 📊 Beautifully formatted output using `tabulate`
- 🧠 Threshold-based intelligent filtering
- 🛠️ Supports Linux, Windows, and macOS
- 💾 Exports results into clean, readable reports
- 🎯 Beginner-friendly usage, no API keys required
- 🔐 Built for ethical hackers, students & sysadmins

---

## 📁 Folder Structure


---

## ⚙️ Installation

Make sure Python 3 is installed.

```bash
git clone https://github.com/<your-username>/chaosLogMonitor.git
cd chaosLogMonitor
pip install -r requirements.txt

##HOW TO USE##
python3 main.py --file logs/access.log --threshold 5 --report reports/output.txt

Flag | Description | Required
--file | Path to the access log file | ✅ Yes
--threshold | Request count to flag IP as suspicious (default: 10) | ❌ Optional
--report | Output file path for saving flagged results | ✅ Yes

   ________  __    __       _______.  ______  __    __     ____    ____  ___
  /  _____||  |  |  |     /       | /      ||  |  |  |     \   \  /   / /   \
 |  |  __  |  |__|  |    |   (----`|  ,----'|  |__|  |      \   \/   / /  ^  \
 |  | |_ | |   __   |     \   \    |  |     |   __   |       \_    _/ /  /_\  \
 |  |__| | |  |  |  | .----)   |   |  `----.|  |  |  |         |  |  /  _____  \
  \______| |__|  |__| |_______/     \______||__|  |__|         |__| /__/     \__\

         chaos_suspicious log monitor v1.0 🔥

+---------------+------------+
| IP Address    | Requests   |
+---------------+------------+
| 192.168.1.100 |     87     |
| 10.0.0.5      |     65     |
+---------------+------------+

© 2025 chaospi — All rights reserved.
Unauthorized copying or distribution of any part of this project is strictly prohibited.

