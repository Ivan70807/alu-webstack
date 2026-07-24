# https_ssl

This project covers DNS subdomain configuration, HAProxy SSL termination with Let's Encrypt certificates, and enforcing HTTPS by redirecting HTTP traffic.

## Tasks

- **0-world_wide_web**: Bash script that audits DNS A records for www, lb-01, web-01, and web-02 subdomains.
- **1-haproxy_ssl_termination**: HAProxy configuration for SSL termination on port 443 using a certbot-issued certificate.
- **2-redirect_http_to_https**: HAProxy configuration that redirects all HTTP traffic to HTTPS with a 301.
