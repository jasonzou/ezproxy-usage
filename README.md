# ezproxy-usage
Using opensearch, dashboard, and logstash to manage EZproxy usage data

## Opensearch and dashboard 

Set up your Docker host environment
- macOS & Windows: In Docker Preferences > Resources, set RAM to at least 4 GB.
- Linux: Ensure vm.max_map_count is set to at least 262144 as per the documentation.
- Download docker-compose.yml into your desired directory
- Run docker-compose up
- Have a nice coffee while everything is downloading and starting up
- Navigate to http://localhost:5601/ for OpenSearch Dashboards
- Login with the default username (admin) and password (admin)
