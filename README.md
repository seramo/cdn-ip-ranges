# CDN IP Ranges

This repository provides a collection of IP ranges for several popular Content Delivery Networks (CDNs), making it useful for configuring firewalls, optimizing networks, analyzing traffic, and especially for enhancing V2Ray scanners.

## Contents

This repository currently includes IP ranges for:

- Cloudflare
- Gcore
- Fastly

Each CDN's IP ranges are detailed in JSON files, such as `cloudflare.json`, which provides separate lists for IPv4 and IPv6 addresses.

## Applications

- **Firewall Configuration:** Control access by allowing or blocking traffic from specific CDNs.
- **Network Optimization:** Improve routing and reduce latency for enhanced performance.
- **Traffic Analysis:** Track and identify CDN traffic sources.
- **V2Ray Scanners:** Use these IP ranges in V2Ray scanners.

## How to Use

1. Clone the repository or download the necessary files:

    ```bash
    git clone https://github.com/seramo/cdn-ip-ranges.git
    ```

2. Implement the IP range lists into your systems or tools.
3. Customize your network or firewall settings as needed.

To directly integrate the JSON files into your applications or scripts, access the raw content using these URLs:

- Cloudflare IP ranges
   ```
   https://raw.githubusercontent.com/seramo/cdn-ip-ranges/main/cloudflare.json
   ```
- Gcore IP ranges
   ```
   https://raw.githubusercontent.com/seramo/cdn-ip-ranges/main/gcore.json
   ```
- Fastly IP ranges
   ```
   https://raw.githubusercontent.com/seramo/cdn-ip-ranges/main/fastly.json
   ```

## Contribution

Contributions and updates are welcome. Please submit changes via a Pull Request.