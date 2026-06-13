# Wireless University Campus Network Design using Cisco Packet Tracer

## Overview
This project presents the design and simulation of a Wireless University Campus Network using Cisco Packet Tracer. The network connects academic buildings, library facilities, IT consulting services, server infrastructure, and hostel areas through a centralized architecture. The implementation provides secure and reliable communication between all network segments while supporting essential university services.

## Objectives
- Design a scalable university campus network.
- Configure wired and wireless connectivity across all locations.
- Implement DNS, Web, and Email services.
- Enable communication between campus and hostel networks.
- Secure router access using SSH authentication.
- Verify network functionality through testing and simulation.

## Network Architecture

### Campus Area
- Academic Block 1 (AB1)
- Academic Block 2 (AB2)
- Dome Building
- Library
- IT Consulting Center
- Server Center

### Hostel Area
- Boys Hostel
- Girls Hostel

### Core Devices
- Main Router
- Campus Router
- Hostel Router
- Campus Switch
- Hostel Switch
- Server Switch
- Wireless Access Points

## IP Addressing Scheme

### Campus Network
- Network: `192.168.1.0/24`
- Gateway: `192.168.1.1`

### Server Network
- Network: `192.168.2.0/24`
- Gateway: `192.168.2.1`

### Hostel Network
- Network: `192.168.3.0/24`
- Gateway: `192.168.3.1`

### Router Links
| Connection | Network |
|------------|---------|
| Main Router ↔ Campus Router | 10.0.0.0/30 |
| Main Router ↔ Hostel Router | 10.0.0.4/30 |

## Services Implemented

### DNS Server
Configured DNS records:
- `www.university.edu`
- `mail.university.edu`

### Web Server
Hosted a university website displaying:
- Welcome message
- University image/banner

### Email Server
Created user accounts:
- `student1@university.edu`
- `staff1@university.edu`

### Wireless Network
- Unique SSID for each building
- Password-protected access points
- Connectivity for laptops and smartphones

## Router Configuration

### Features
- Interface IP configuration
- Static routing
- Console security
- SSH remote access

### Security Credentials

| Router | Console Password | SSH Password |
|----------|----------------|-------------|
| Main Router | cisco | admin |
| Campus Router | uni@123 | admin |
| Hostel Router | uni@123 | admin |

## Testing Performed

✔ Device-to-device ping tests

✔ Web server accessibility through browser

✔ Email communication between student and staff

✔ DNS name resolution verification

✔ Packet flow analysis using Simulation Mode

## Technologies Used
- Cisco Packet Tracer
- TCP/IP Networking
- Static Routing
- DNS
- Web Server
- Email Server
- Wireless Networking
- SSH Security

## Project Outcomes
The simulated network successfully provides secure communication between all university departments and hostel facilities. All configured services including DNS, Web, Email, Wireless Connectivity, and Routing function correctly, demonstrating a realistic campus networking environment.

## Author
Poornima Nethranjalee 

## License
This project is created for educational and academic purposes.
