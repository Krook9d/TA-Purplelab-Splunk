# PurpleLab Integration App for Splunk

## Overview

The PurpleLab Integration App for Splunk enhances your security operations by seamlessly integrating with PurpleLab. This app enables users to effortlessly launch Atomic Red Team tests on the PurpleLab platform and conduct threat hunting directly from within Splunk's interface. Designed for security analysts and operations teams, it streamlines the process of testing and validating detection rules against a wide range of simulated attack techniques.

## Features

- **Atomic Red Team Test Execution**: Initiate Atomic Red Team tests on the PurpleLab platform directly from Splunk.
- **Threat Hunting Dashboard**: Utilize a dedicated dashboard within Splunk for efficient threat hunting, powered by data from PurpleLab.
- **Seamless Integration**: Easy setup and configuration to interconnect PurpleLab with Splunk for enhanced security operations.


## Requierement

Some configuration steps are required to fully integrate the app with your PurpleLab environment:

1. Ensure to have sysmon on the VM of Purplelab installed and well configured
2. Install Microsoft Sysmon Add-on & Sysmon App for Splunk

## Installation

To install the PurpleLab Integration App for Splunk, follow these simple steps:

1. Download the app package from the release page
2. In Splunk, navigate to `Manage Apps > Install app from file`.
3. Upload the downloaded app package and click `Upload`.
4. Once installed, restart Splunk to apply the changes.

## Using the App

### Launching Atomic Red Team Tests

1. Go to the PurpleLab Integration App dashboard within Splunk.
2. Select the `Atomic Red Team` dashboard.
3. Choose the desired tests and type it on "List technique test" to have further information and click ENTER, to execute a test, type the id on Technique ID MITRE ATTACK and click `Submit`.

### Threat Hunting

1. Access the `Hunting` dashboard from the app's main menu.
2. Use the provided filters and search capabilities to hunt for threats based on the data collected from PurpleLab VM.

## Screenshots

![PurpleLab Integration Dashboard](/Purplelabsplunkaddonhunting.png)
*PurpleLab Integration Dashboard*

![Threat Hunting Dashboard](/Purplelabsplunkaddon.png)
*Threat Hunting Dashboard*

## Support

For support and further assistance, please open an issue

## License

This app is provided under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). See LICENSE for more details.
