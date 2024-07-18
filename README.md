# Personal use - not real

# Joomla Vulnerability Checker - CVE-2023-23752
This tool checks for the presence of the CVE-2023-23752 vulnerability in Joomla websites. The vulnerability allows attackers to execute arbitrary code on the affected Joomla installations.

# Requirements
Python 3.x
requests library
Installation

# To install the required requests library, use:

`pip install requests`

# Usage
Run the script with the following command:

`python cve_2023_23752_checker.py <url>`
Replace <url> with the target Joomla website URL you want to check.

# Example
`python cve_2023_23752_checker.py http://example.com`

# Output
The script will output whether the provided Joomla URL is vulnerable or not.

[+] http://example.com is vulnerable - indicates that the website is vulnerable.
[-] http://example.com is not vulnerable - indicates that the website is not vulnerable.
