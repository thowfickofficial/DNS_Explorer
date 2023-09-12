# DNS Explorer 🌐

## Overview

DNS Explorer is a powerful Python tool designed to help you explore and retrieve DNS (Domain Name System) information for one or more domain names or IP addresses. This tool utilizes asynchronous DNS queries to quickly and efficiently fetch various DNS record types, providing comprehensive insights into a target's DNS configuration.

## Features

### 1. Multifaceted DNS Lookup

- **Versatile Queries**: Perform DNS lookups for multiple domain names or IP addresses simultaneously, separated by spaces.

- **Custom Record Types**: Specify DNS record types (e.g., 'A', 'AAAA', 'MX') to retrieve precise information tailored to your needs.

- **Reverse DNS Lookup**: Optionally perform reverse DNS lookups to map IP addresses to domain names.

### 2. Efficient Asynchronous Queries

- **Swift Execution**: Utilizes asynchronous queries for speedy DNS information retrieval.

- **Results Caching**: Cache DNS query results to improve performance for frequently looked-up domains.

### 3. User-Friendly Interface

- **Interactive**: Interactive command-line interface that guides you through each step.

- **Output Options**: Choose to display results on the screen or save them to a specified output file.

## Getting Started

1. Run the script using `python DNS_Explorer.py` in your terminal.

2. Enter one or more domain names or IP addresses separated by spaces.

3. Specify the DNS record types you want to retrieve (e.g., 'A AAAA MX').

4. Choose whether to perform reverse DNS lookups (IP to domain).

5. Optionally, specify an output file to save the results.

6. Review the comprehensive DNS information retrieved.

## Requirements

- Python 3.x
- Required Python packages (install via `pip`):
  - `aiohttp`
  - `dns.resolver`
  - `pyfiglet`
  - `click`

## Usage

- Explore DNS information for multiple domains or IPs.
- Retrieve specific DNS record types.
- Perform reverse DNS lookups when needed.
- Save results to a file for future reference.


🔍 **Discover DNS Insights with DNS Explorer!** 🚀
