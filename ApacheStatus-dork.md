# Exposed Apache Server Status Pages

- **Dork**: inurl:"/server-status" intitle:"Apache Status"
- **Purpose**: Locates Apache server status pages, combining `/server-status` in the URL with "Apache Status" in the title to reduce false positives.
- **Notes**:
  - Exposing server status pages publicly can reveal resource usage, request handling, and server uptime information.
  - This information can be leveraged in reconnaissance to better understand server load and possible entry points.
