# Ansible-based VM Monitoring Automation

A simple and scalable automation project that monitors AWS EC2 Linux servers using Ansible (agentless). It collects CPU, Memory, and Disk usage metrics and generates an HTML health report, which is automatically sent via email.

---

### 🔹 Key Features
- Monitors AWS EC2 VMs using SSH — no agent required
- HTML dashboard with performance status indicators
- Automated email alerts for proactive issue detection
- Fully Infrastructure as Code using Ansible

---

### 🛠 Tech Stack
Ansible • AWS EC2 • Linux

---

### ▶️ How to Run
```bash
ansible-playbook collect_metrics.yaml
ansible-playbook send_report.yaml

---

## 📸 Project Demo

### VM Health Report Email
![VM Report](screenshots/vm-report-email.png)

### Ansible Execution Output
![Ansible Output](screenshots/ansible-output.png)

### AWS EC2 Instances
![AWS EC2 Instances](screenshots/aws-ec2.png)

