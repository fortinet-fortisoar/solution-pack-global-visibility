[Home](../README.md) |
|--------------------------------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.
2. From the list of solution pack that appears, search for and select **Global Visibility**.
3. Click the **Global Visibility** solution pack card.
4. Click **Install** on the lower part of the screen to begin the installation.

## Prerequisites
The **Global Visibility** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| Solution Pack Name | Version         | Purpose                                       |
|:-------------------|:----------------|:----------------------------------------------|
| SOAR Framework     | v2.0.1 or later | Required for Alerts, Assets, Incident modules |

Before installing the FortiSOAR Global Visibility Solution Pack, ensure the following prerequisites are met:

1. A working FortiSOAR instance at each site
2. Access to the FortiSOAR API of each instance
3. User credentials with appropriate permissions to access data
4. Remote FortiSOAR connector for Global Visibility data aggregation

# Configuration

- The **Global Visibility** solution pack launches the configuration wizard as soon as it finishes installation. However, You can also click the <strong>Configure</strong> button on the solution pack's installation page to configure the sites.


- Remote FortiSOAR connector installs with the solution pack. You need to configure the connector with relevant sites to use the dashboard widgets.

    - **Remote FortiSOAR** - To configure and use the Remote FortiSOAR connector, refer to [Configuring Remote FortiSOAR](https://docs.fortinet.com/fortisoar/connectors/remotefsr)

# Next Steps
| [Usage](./usage.md) | [Contents](./contents.md) |
|---------------------|---------------------------|