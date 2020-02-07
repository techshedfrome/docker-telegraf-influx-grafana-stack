# Docker Stack for Telegraf InfluxDB Grafana

This configuration icludes Grafana dashboards, connected to InfluxDB for:
* Telegraf - monitoring the host machine
* Luftdate - monitoring data pushed into the Luftdaten database in InfluxDb from [AirRohr](https://luftdaten.info/en/construction-manual/) pollution sensor devices 

## Start Docker Stack

```bash
docker-compose up
```

Grafana
URL: http://localhost:3000 
User: admin 
Password: admin 

Statsd agent (telegraf) Port 8125 (UDP)


![Example Screenshot](./example.png?raw=true "Example Screenshot")
