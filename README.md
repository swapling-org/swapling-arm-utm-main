# swapling-arm-utm-main
Main repository for the Swapling UTM project for ARM devices

...
Project Swapling started to build an Unified Threat Management application that includes

Routing Capabilities
-- L4 Static Routing
-- SNAT and DNAT capabilities

Wireless Capabilities
-- Access Point capabilities
-- Hotspot capabilities with multiple authentication mechanisms ( detailed to be added )
-- Exemption by Mac adresses

Threat Management Capabilities
-- Statefull firewall
-- Anti-virus controll on all passing TCP traffic with ability to limit per firewall rules
-- DNS based web filter (both via a DNS server and traffic sniffing)
-- HTTP filtering without proxy
-- HTTPS filtering via SNI and without proxy

URL Categorization
-- A seperate, web service based URL categorization and database creation project will be implemented. It may or may not be a free service 
( depending on the costs, but 3rd party solution should also be allowed )

Windows and Linux endpoint agents
-- Report logged in users and changes
-- Disable execution of executables via command from the Swapling UTM

Logging
-- All filters and firewall rule based packets including the accepted packets should be logged and timestamped
-- A legally acceptable timestamping mechanisms should be implemented
-- Corresponding legal situation may vary in time, currently supported countries will be listed here
-- The system and logging should be lightweight such that with a 16GB flash card, all the application, underlying operating system and 
logs should work fine with at least 6 months of log saving capacity. All related performence reports should take this goal into 
consideration

Management
-- Local user system
-- Radiues / Tacacts support
-- Active directory group integration with real-time control on login
-- WEB GUI
-- CLI accessable via SSH

Project Swapling is licensed under GNU GPLv3 
...
