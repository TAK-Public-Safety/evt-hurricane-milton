# Pulsepoint Integration
PulsePoint integration requires you to run the PulseCOT configured to pull in the agencies you want. Steps:
1) Create a user certificate for the integration and download the .pem and .key files
2) Download [PulseCOT](https://github.com/snstac/pulsecot)
3) Follow the steps [here](https://github.com/snstac/pulsecot/issues/7) to set things up

Here's a sample config.ini with a large number of Florida agencies preconfigured
```
[pulsecot]
POLL_INTERVAL=90
AGENCY_IDS=28042,EMS1236,EMS1296,CCSO1,EMS1203,14162,65060,07212,5102x,16072,17022,X4015
COT_URL=tls://<yourserver>:8089
PYTAK_TLS_CLIENT_CERT=<REPLACEWITHUSER>.pem
PYTAK_TLS_CLIENT_KEY=<REPLACEWITHUSER>.nopass.key
PYTAK_TLS_DONT_VERIFY=1
```
