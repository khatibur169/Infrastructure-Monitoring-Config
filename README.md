# Infrastructure Monitoring Configuration

This repository contains configuration files for setting up and managing monitoring infrastructure using Datadog, Prometheus, and Grafana.

## Purpose

The purpose of this project is to provide a centralized location for maintaining configurations related to monitoring tools used within our infrastructure. By utilizing Git version control and GitHub collaboration, it aims to streamline the management of monitoring configurations for Datadog, Prometheus, and Grafana.

## Folder Structure

The repository is structured as follows:

- **Datadog**: Contains configurations for Datadog monitoring.
- **Prometheus**: Includes Prometheus configuration files.
- **Grafana**: Holds Grafana configuration settings.

## Configuration Files

### Datadog:
- `datadog.yaml`: Configuration file for Datadog monitoring. Includes configurations for agents, integrations, and monitoring setup.
- `dashboards.yaml`: Defines a simple dashboard showing CPU usage for various hosts and a threshold marker at 80%.
- `monitors.yaml`: Sets up a monitor to alert when the CPU usage drops below 20% on any host in the production environment.

### Prometheus:
- `prometheus.yaml`: Main configuration file for Prometheus. Defines scrape targets and global settings.
- `prometheus.rules.yaml`: Adjust the rules according to your infrastructure and monitoring needs.

### Grafana:
- `grafana.ini`: Grafana configuration file containing settings for the Grafana server, database connections, and security configurations.

## How to Contribute

1. **Clone the Repository:**
   ```bash
   git clone <repository_URL>
   cd Infrastructure-Monitoring-Config
2. **Make Changes:**
- Navigate to the specific tool's folder (e.g. Datadog, Prometheus, Grafana).
- Modify or add configuration files as needed.
3. **Commit Changes:**
   ```bash
   git add .
   git commit -m "Brief description of changes made"
4. **Push Changes:**
   ```bash
   git push origin main
5. **Create Pull Requests:**
- If working in branches, create pull requests detailing the changes for review.
- Collaborators can review and discuss proposed changes before merging.

## Usage
1. **Datadog Configuration:**
- Update `datadog.yaml` in the Datadog folder with the appropriate configurations for agents, integrations, and monitoring setup.

2. **Prometheus Configuration:**

- Update `prometheus.yml` in the Prometheus folder with the appropriate scrape targets and global settings.

3. **Grafana Configuration:**
- Update `grafana.ini` in the Grafana folder with necessary settings for the Grafana server, database connections, and security configurations.

4. **Collaboration:**
- Collaborators can fork the repository and submit pull requests for enhancements or fixes.

##  Additional Information
<h>For detailed instructions and advanced setups regarding each monitoring tool, refer to their respective documentation:<h>

- [Datadog Documentation](https://prometheus.io/docs/prometheus/latest/configuration/configuration/)
- [Prometheus Documentation](https://docs.datadoghq.com/observability_pipelines/configurations/?tab=yaml)
- [Grafana Documentation](https://grafana.com/docs/grafana/latest/setup-grafana/configure-grafana/)

<b>Feel free to reach out for any questions or further information.<b>



