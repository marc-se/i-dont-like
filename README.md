# i-dont-like
## Custom Pihole Blacklist

This repository hosts a custom list of domains that I choose to block using **Pihole**.

The list is maintained primarily to enhance my privacy, block specific tracking/telemetry, and remove domains that serve content I find undesirable or distracting.

## Usage

To use this list in your Pihole installation, follow these steps:

1.  Navigate to your **Pihole admin interface**.
2.  Go to the **"Manage Lists"** section (often found under *Lists*).
3.  Add the raw URL for the `domains.txt` file from this repository:
    `https://raw.githubusercontent.com/marc-se/i-dont-like/main/domains.txt`
4.  Click **"Add Blocklist"** and then update your gravity list for the changes to take effect. (via **Tools** > **Update Gravity** > **Update**)

## Format

The list is a simple text file (`domains.txt`) where **each blocked domain is on a new line**.
