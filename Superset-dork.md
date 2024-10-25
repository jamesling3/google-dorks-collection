# Exposed Apache Superset Servers

- **Dork**: intitle:"Superset" inurl:"/superset/dashboard/"
- **Purpose**: Identifies exposed Apache Superset dashboards, which could disclose sensitive data unintentionally made public.
- **Notes**:
  - Superset dashboards may contain sensitive analytics, data visualizations, or internal data metrics.
  - Public access to these dashboards can reveal information about an organization’s data, processes, or infrastructure.
  - Exposed Superset instances could potentially lead to data leaks or give insights useful in further exploitation.
