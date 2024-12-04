# Enterprise Campus Network Design

## Project Overview  
This project involves designing a secure **Campus Area Network (CAN)** for an enterprise with two locations: **Location A** and **Location B**. The focus was on implementing a secure and functional network architecture that meets specific access and service requirements.

## Network Architecture  
- **Locations:**  
  - **Location A**  
  - **Location B**  

- **Main Server:**  
  - Located in **Location B**  
  - IP Address: `172.18.51.1`  
  - **Access Control:**  
    - Only devices **PC0** to **PC5** are allowed to access the server.  
    - Access is limited to the **web service** only.  
    - Devices cannot **ping** the server but can access the specified service.

## Key Features  
- **Restricted Access:** Ensures security by allowing only designated PCs to interact with the main server.  
- **Service-Specific Access:** Implements access control at the service level (web service).  
- **Two-Layered Network Design:**  
  - Separate locations with dedicated functionalities.  
  - Centralized server in **Location B** to serve authorized devices.  

## Tools & Technologies  
- Network simulation software (e.g., Cisco Packet Tracer or GNS3)  
- IP addressing and subnetting  
- Access control and firewall configurations
