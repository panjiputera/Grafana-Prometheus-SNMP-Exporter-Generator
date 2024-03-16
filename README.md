# mikrotik-monitoring
Custom grafana monitoring for mikrotik with snmp exporter from (https://github.com/ajidiyantoro/mikrotik-monitoring) and add new snmp.yml from snmp_exporter generator mib

Before using grafana:
1. make sure you alredy enable snmp in your device ex:mikrotik
2. add your snmp device in prometheus.yml

![image](https://github.com/panjiputera/mikrotik-monitoring/assets/96469303/7488432b-a7a1-45a3-a10f-6cef286ac412)


4. Next go up your docker compose

How to use

1. Just put all in one folder and run docker-compose up -d
2. Access Grafana from http://localhost:3000
