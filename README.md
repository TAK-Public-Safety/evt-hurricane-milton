# Hurricane Milton Response
Coordination of Hurricane Milton Response between federal, state and local public safety organizations. Available as a single page at [https://milton.takps.org](https://milton.takps.org) backed by a [GitHub repository](https://github.com/TAK-Public-Safety/evt-hurricane-milton)

## Table of Contents
* [Post Storm Imagery](#post-storm-imagery)
* [TAK Servers](#tak-servers)
* [Team Colors](#team-colors)
* [Data Packages and Resources](#data-packages-and-resources)
* [Alternate Comms](#alternate-comms)
* [Power Outage Data](#power-outage-data)
* [TAK Server Plugin for FL511](#tak-server-plugin-for-fl511)
* [PulsePoint Integration](#pulsepoint-integration)

## Post Storm Imagery
(From [Joseph Elfelt](https://mappingsupport.com))

NOAA has started to post high resolution aerial photos taken over areas that may have been affected by Hurricane Milton.  So far, 4 flights from October 11 have been posted.  You can add that data to ATAK using this MultiLayer XML file:

[https://mappingsupport.com/p2/special_maps/disaster/NOAA_damage_aerials/noaa_aerials_2024_milton.xml](https://mappingsupport.com/p2/special_maps/disaster/NOAA_damage_aerials/noaa_aerials_2024_milton.xml)

As additional flights take place I will update this XML file.

To view this data in ATAK as an overlay you need to *manually* placed the XML file in the ATAK grg folder.  All other ways to access this data in ATAK will treat the data as a basemap. Reminder: ATAK cannot open the WMTS capabilities file NOAA provides.

Master link to NOAA disaster imagery:
[https://storms.ngs.noaa.gov/](https://storms.ngs.noaa.gov/)

## TAK Servers
The following TAK Servers are available:

- LEO / Federal - [https://milton.tak.gov](https://milton.tak.gov). You'll need to reach out to takrequest at leo.gov for credentials
- SOCOM: CTIC is hosting the server. Contact your appropriate authorities
- FLNG / FLSAR - PAR / BAH is hosting the Sit(X) server for these groups. If you don't have contact info reach out below and we'll connect you
- Florida public safety / responders: [https://fltak.us](https://fltak.us) should be your starting point. Registration / contact information is available there
- TAK Public Safety has a last resort server at [https://takserver.takps.org](https://takserver.takps.org)

If you are authorized to access any of the above and need contact information reach out to hurricanemilton at takps.org and we'll get you routed to the right spot

A locator URL is available at [https://takserver.takps.org:8446/locate/index.html](https://takserver.takps.org:8446/locate/index.html) which will broadcast locations through the federated groups. Please reach out to the above takps email address for more information

## Team Colors
* For users of FLTAK please refer to their [callsigns](https://fltak.cdrp.net/callsigns) page for official colors
* For federal users, please refer to your local protocols for team colors and callsigns
* For all others, these are suggested team colors for responders

![JPEG image-43BA-91F0-A4-0](https://github.com/user-attachments/assets/52907664-fa0d-415a-950b-bd1d72dac640)

## Data Packages and Resources
* [FEMA.REGIONS.nws.zip](https://github.com/TAK-Public-Safety/evt-hurricane-milton/raw/refs/heads/main/FEMA.REGIONS.nws.zip)
* [Fire_and_Emergency_Medical_Service__EMS__Stations.kml](https://github.com/TAK-Public-Safety/evt-hurricane-milton/raw/refs/heads/main/Fire_and_Emergency_Medical_Service__EMS__Stations.kml)
* [hospital_helipad_20240905.xlsx](https://github.com/TAK-Public-Safety/evt-hurricane-milton/raw/refs/heads/main/hospital_helipad_20240905.xlsx)
* [NWS KML Data Package Zip](https://github.com/user-attachments/files/17286314/NHC_MILTON_KML_LINKS.zip)
* [Animal_Shelter_MILTON_HADRv1-1.kmz](https://github.com/TAK-Public-Safety/evt-hurricane-milton/raw/refs/heads/main/Animal_Shelter_MILTON_HADRv1-1.kmz)
* GeoJSONs for various Florida assets is available at [https://github.com/TAK-Public-Safety/evt-hurricane-milton/tree/main/geojson](https://github.com/TAK-Public-Safety/evt-hurricane-milton/tree/main/geojson)

## Alternate Comms
* [The Hurricane Watch Net](https://hwn.org) is active on 14.325.00 MHz (USB) and 7.268.00 MHz (LSB)

## Power Outage Data
* Power Outage Map for Florida [https://poweroutage.us/area/state/florida](https://poweroutage.us/area/state/florida)
* Josh Fuller has created a KML network link available at [https://milton-tak.ddns.network/](https://milton-tak.ddns.network/)
* Source code is available at [https://github.com/joshuafuller/PowerOutage2ATAK](https://github.com/joshuafuller/PowerOutage2ATAK)

## TAK Server Plugin for FL511
Raytheon BBN (Nate Soule) has developed a TAK Server plugin for FL511 Data. Refer to [https://github.com/TAK-Public-Safety/evt-hurricane-milton/tree/main/fl511-plugin](https://github.com/TAK-Public-Safety/evt-hurricane-milton/tree/main/fl511-plugin) to download and install instructions

## PulsePoint Integration
* If you want a feed of PulsePoint data, you can federate to the HurricaneMiltonDataFeed on the TAKPS Servers or follow the steps [here](https://github.com/TAK-Public-Safety/evt-hurricane-milton/tree/main/pulsepoint)
