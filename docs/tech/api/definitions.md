# XNET Data Fields Overview

## 1. **status**

### Organization status
- **active**: 
    - The organization’s org-owner status is "active".
- **inactive**: 
    - The organization’s org-owner status is "inactive".
- **suspended**: 
    - This organization has been suspended for administrative or compliance reasons. It remains in our records but it’s venues and devices are no longer active within the XNET network.

### Member status
- **active**: 
    - The member has accepted the organization invite.
- **inactive**: 
    - The member's invitation has expired without a response.
- **declined**: 
    - The member has declined the invitation.

### User status
- **active**: 
    - The user's email is verified.
- **inactive**: 
    - The user's email is unverified.
- **suspended**: 
    - This user has been suspended for administrative or compliance reasons. They remain in our records, but their account is no longer active within the XNET network.

### Venue status
- **active**: 
    - Devices are registered under this venue.
    - The site is qualified by XNET.
- **inactive**: 
    - No devices are registered under this venue.
    - The venue is not qualified by XNET (Qualification may take up to 30 days).
- **suspended**: 
    - This venue has been suspended for administrative or compliance reasons. It remains in our records, but its venue and devices are no longer active within the XNET network.

### Device status
- **active**: 
    - The device is assigned to a venue.
- **inactive**: 
    - The device is not assigned to any venue.
- **suspended**: 
    - This access point has been suspended for administrative or compliance reasons.  It remains in our records, but is no longer active within the XNET network.
- **rma**: 
    - The access point has been approved for Return Merchandise Authorization (RMA) by XNET.

### Venue Qualification status
- **qualified**: 
    - The venue meets all required standards and criteria.
- **unqualified**: 
    - The venue does not meet the necessary standards or criteria.
- **pending**: 
    - The venue is currently under review and awaiting a qualification decision.

---

## 2. **orgrole**

### Member
- **org-owner**: 
    - Possesses all organization administrative capabilities; only this role can remain unchanged by others.
- **org-admin**: 
    - Responsible for organization wallet management, member management, device management, and venue management.
- **org-manager**: 
    - Handles device management, and venue management.
- **org-viewer**: 
    - Can view organization resources without making any modifications.

!!! Important
    Specifics on orgrole endpoint access can be found in this
    <a href="/img/api/orgrole_matrix.pdf" target="_blank" data-fancybox="gallery">matrix</a>

---

## 3. **type**

### Organization
- **community**: 
    - A community builder deploying XNET access points individually (default type for all users).
- **isp/msp**: 
    - Companies providing internet access to businesses/consumers or working with a Managed Service Provider (MSP).
    - ISP/MSP partners must reach out to XNET for approval.
- **mno/mvno**: 
    - A Mobile Network Operator/Virtual Mobile Network Operator customer that offloads cellular data through XNET.

---

## 4. **tags**
### Venue and Device
- **tags**: 
    - Labels used to categorize or identify resources such as venues or devices.
    - Can be any string value chosen by the user.

---

## 5. **venuedesc**

### Venue
- amusement park
- aquarium
- attorney office
- automotive service station
- bank
- bar
- boarding house
- bus stop
- coffee shop
- college
- convention center
- dentist
- doctor
- emergency coordination center
- factory
- gas station
- grocery market
- group home
- hospital
- hotel
- kiosk
- library
- long‑term care facility
- motel
- museum
- park
- passenger terminal
- place of worship
- police station
- post office
- prison or jail
- professional office
- rehabilitation center
- rest area
- restaurant
- retail store
- school
- shopping mall
- stadium
- theater
- university
- zoo or aquarium

---

## 6. **isp**

### isp.name 

- Alaska Communications
- Allo Communications
- AT&T
- Astound Broadband (Wave, RCN)
- Blue Ridge Communications
- Breezeline (formerly Atlantic Broadband)
- Brigham Net
- Broadband VI
- Buckeye Broadband
- Cable One
- Chat Mobility
- CenturyLink
- Cincinnati Bell (altafiber)
- Clearwave Communications
- Community Fiber Solutions
- Consolidated Communications
- Cox
- DigitalPath
- EarthLink
- EPB Fiber Optics
- Fibersphere Communications
- Frontier Communications
- Google Fiber
- Grande Communications
- Hargray Communications
- Hawaiian Telcom
- Hotwire Communications
- HughesNet
- Kinetic by Windstream
- Lumos Networks
- Mediacom
- Mediastream
- MetroNet
- Midco
- Municipal Fiber Networks
- New Hampshire FastRoads
- NorthState Communications
- Optimum (Altice USA)
- RCN
- Rise Broadband
- RiverStreet Networks
- Sonic
- Spectrum (Charter Communications)
- T-Mobile Home Internet
- TDS Telecom
- Verizon Fios
- Viasat (Exede)
- Windstream
- Xfinity
- Ziply Fiber
- OTHER

### isp.class
- **business**: 
    - Intended for commercial or enterprise use.
- **consumer**: 
    - Intended for residential or general consumer use.

### isp.connection
- **Fiber**: 
    - Fiber Optic connection.
- **Cable**: 
    - Cable broadband.
- **DSL**: 
    - Digital Subscriber Line (telephone line).
- **Satellite**: 
    - Satellite broadband for remote areas.
- **Dial-Up**: 
    - Low-speed, traditional dial-up connection.

### isp.bandwidth
- 0-99Mbps
- 100-199Mbps
- 200-299Mbps
- 300-499Mbps
- 500-999Mbps
- 1-1.99Gbps
- 2Gbps+

### isp.ispsecurity
- **DefaultRouterSecurity**: 
    - Default security settings on the router.
- **Firewall (L3) / Next Gen Firewall**: 
    - Traditional or advanced firewall security.
- **IDS / IPS**: 
    - Intrusion Detection/Prevention Systems.
- **VPN Gateway**: 
    - Secure gateway for VPN connections.
- **Network Segmentation (L2)**: 
    - Data link layer security.
- **Network Segmentation (L3) (VLANS)**: 
    - VLAN network segmentation.
- **DNS Sinkhole / Redirection**: 
    - Blocks malicious DNS traffic.
- **Physical Security (Cages/Locks)**: 
    - Physical security measures for network hardware.
