## RemoteCDP
RemoteCDP is a Docker container designed to run on a VPS with a dedicated IP address. It sets up Chrome DevTools Protocol (CDP) behind a Squid reverse proxy, enabling remote access to a headless Chrome browser instance from outside the container. This allows remote code execution for tasks such as web testing and scraping.

By routing CDP traffic through Squid’s reverse proxy and leveraging its caching features, RemoteCDP reduces duplicate page downloads across the network, improving efficiency. This setup is intended to be deployed on a VPS, where the Docker container runs continuously to provide a stable, remotely accessible browser environment for an LLM agent or other automation scripts.

