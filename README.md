# Hi, I'm Pravinash 👋

**Cybersecurity | Security Operations | Threat Detection & Log Analysis**

I enjoy building hands-on security projects that explore how suspicious activity is detected, investigated, visualised, and responded to. My current portfolio focuses on honeypot-based IP blocking and Splunk-based SOC monitoring.

## 🧪 Explore the interactive CyberLab

I built a visual, beginner-friendly demonstration to make both projects easier to understand. Click through each stage, follow the data flow, try a safe simulated event counter, and explore illustrative SOC dashboard data.

**Website source:** [Open `index.html`](./index.html) · **Publish guide:** see below.

> The website is an educational simulation. It does not connect to live security tools, send attack traffic, or change firewall rules. Dashboard values are illustrative demo data.

## 🚀 Featured projects

### 🛡️ Automated IP Blacklisting Using Honeypot Logs
A lab project exploring how Cowrie honeypot events can be inspected with Python and how a threshold-based rule can add an iptables block rule. The project also documents an ELK visualisation path.

**Tools:** Cowrie · Python · iptables · Logstash · Elasticsearch · Kibana  
[View repository →](https://github.com/Pravinashrajendran/Automated-IP-Blacklisting-Using-honeypot-Logs)

### 📊 Splunk SOC Threat Detection & Log Analysis
A hands-on SOC monitoring project using SSH, Apache, and example JSON logs to practise SPL searches and investigate suspicious patterns through dashboards.

**Tools:** Splunk Enterprise · SPL · SSH logs · Apache logs · JSON  
[View repository →](https://github.com/Pravinashrajendran/splunk-soc-threat-detection)

### 🧠 DDoS Detection Using LSTM
Research project exploring a data-driven approach to DDoS detection using an LSTM model and the CIC-DDoS2019 dataset.

[View repository →](https://github.com/Pravinashrajendran/A-Data-Driven-Generalizability-Approach-for-DDoS-Detection-Using-LSTM) *(repository may be private)*

## 🧰 Technologies explored

- **Security monitoring:** Splunk, SPL, log analysis, detection rules
- **Honeypots & response:** Cowrie, Python, Linux firewall rules
- **Log pipelines & visualisation:** Logstash, Elasticsearch, Kibana
- **Data & research:** Python, LSTM-based classification, CIC-DDoS2019

## 🌐 Publish the interactive website

To make the CyberLab available as a public website:
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. After GitHub Pages finishes publishing, the site should be available at `https://pravinashrajendran.github.io/pravinashrajendran/`.

The site source is in [`index.html`](./index.html). You can also clone this repository and open that file in a browser or VS Code.

## 📫 Find me on GitHub

[github.com/Pravinashrajendran](https://github.com/Pravinashrajendran)

---

*Project descriptions are kept aligned with the documented implementations; simulated values and planned improvements are not presented as live results.*
