# Steps Taken — Network Troubleshooting Lab

1. Opened Command Prompt.
2. Ran `ipconfig` to review:
   - IPv4 address
   - Default gateway
   - DNS servers
3. Tested internet connectivity with:
   - `ping 8.8.8.8`
4. Tested DNS resolution with:
   - `ping google.com`
5. Used `tracert google.com` to examine the route taken to reach the destination.
6. Flushed the DNS cache using:
   - `ipconfig /flushdns`
7. Re-ran connectivity tests to confirm behavior after changes.
