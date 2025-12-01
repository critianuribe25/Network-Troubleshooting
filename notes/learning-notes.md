# Learning Notes — Network Troubleshooting

- If `ping 8.8.8.8` works but `ping google.com` fails, the issue is usually DNS-related.
- `ipconfig` quickly shows the current IP address, gateway, and DNS servers.
- `tracert` helps identify where along the route packets are being dropped or delayed.
- Flushing DNS can fix issues caused by stale or incorrect cache entries.
