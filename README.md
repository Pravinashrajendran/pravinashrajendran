# CyberLab — Interactive Cybersecurity Project Explorer

A beginner-friendly visual website that explains the flow, purpose, and limitations of two cybersecurity projects.

## Open locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser, or open the folder in VS Code and use Live Server.
3. Select a project, click each pipeline stage, and use the honeypot simulator or Splunk sample-event filter.

## Website features
- Interactive architecture stages with plain-English explanations.
- Safe honeypot event-count simulation. It does **not** send traffic or modify a firewall.
- Illustrative Splunk dashboard and searchable sample events. The metrics are demo data, not live Splunk results.
- Glossary and detection-to-response learning overview.

## Projects shown
- [Automated IP Blacklisting Using Honeypot Logs](https://github.com/Pravinashrajendran/Automated-IP-Blacklisting-Using-honeypot-Logs)
- [Splunk SOC Threat Detection](https://github.com/Pravinashrajendran/splunk-soc-threat-detection)

## Publish as a website with GitHub Pages
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose branch **main** and folder **/(root)**, then save.
4. Wait for GitHub Pages to publish. The URL is usually `https://pravinashrajendran.github.io/pravinashrajendran/`.

The Pages setting must be enabled in GitHub settings; this repository integration cannot enable it automatically.

## Safety and accuracy
This is an educational front-end only. It does not connect to Cowrie, iptables, Elasticsearch, Kibana, or Splunk. No live telemetry is loaded. Sample events and dashboard figures are illustrative. Review real detection logic and validate a source IP before blocking it.
