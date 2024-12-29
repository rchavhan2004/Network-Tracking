This Python project converts network traffic data from a PCAP file into a KML file, enabling visualization of geolocated IP addresses in tools like Google Earth. It uses dpkt for packet parsing, pygeoip for IP geolocation, and socket for IP manipulation.

Features
Network Traffic Parsing: Extracts source and destination IPs from PCAP files.
IP Geolocation: Resolves IP addresses to geographical coordinates using GeoLiteCity.dat.
KML Generation: Creates KML files for easy import and visualization in Google Earth.
