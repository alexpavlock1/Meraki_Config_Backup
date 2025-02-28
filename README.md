# Meraki_Config_Backup

# READ_ME = """
# === PREREQUISITES ===
# Use with Meraki Python SDK @ github.com/meraki/dashboard-api-python/ & install required libraries with
# pip[3] install -r requirements.txt 

# === DESCRIPTION ===
# This script iterates through a dashboard organization and backs up the configuration for the org, networks & templates, 
# and devices, for the config settings that have API endpoint support.

# === USAGE ===
# python[3] backup_configs.py -o <org_id> [-k <api_key>] [-t <tag>] [-y] [-e <template_name>] [-a]

# Required parameters:
#   -o <org_id>           : Target organization ID.
#   -k <api_key>          : Dashboard API key. Can also be passed via MERAKI_DASHBOARD_API_KEY environment variable.

# Optional parameters:
#   -t <tag>              : Filter to only backup networks with this tag.
#   -y                    : Auto-confirm, answer yes to all prompts.
#   -e <template_name>    : Back up a specific template by name.
#   -a                    : Back up all templates (no networks).

# Note: either -e <template_name> or -a can be used to enable template-only mode.

# API key can, and is recommended to, be set as an environment variable named MERAKI_DASHBOARD_API_KEY. 
# """
