# Installing XNET WiFi Devices

Installing **XNET WiFi devices** involves a blend of careful planning, technical know-how, and adherence to best practices. Whether you're setting up an indoor or outdoor network, this guide will walk you through the process step-by-step to ensure a successful and efficient installation. **From pre-installation planning to post-installation checks,** this article covers everything you need to know to get your XNET WiFi devices up and running effectively.

______

## Pre-Installation Planning

### Verifying XNET AP Operation Before Installation Day

Before you proceed with installing any **XNET access point (AP)**, it’s crucial to **verify its operation ahead of the installation day**. This step is essential to avoid potential issues during the actual installation. You can do this by:

1. **Plugging the AP into networking and power:** Ensure the device is powered up and connected to the network.
2. **Completing the registration process:** Follow the steps provided by XNET to register the device. This typically involves entering the AP's serial number and completing any required setup procedures.
3. **Checking for the "XNET" SSID:** After registration, an "XNET" SSID should become visible. If you don’t see an "XNET" SSID, this indicates a problem with the AP’s configuration or network connection.

If the "XNET" SSID doesn’t appear, it’s important to **submit a support ticket** on the [XNET Discord](https://discord.com/invite/xnet) to troubleshoot the issue before the installation day. Addressing these problems in advance will save time and prevent delays during the actual deployment.

### Conducting Site Surveys and Assessing the Installation Environment

Before installing any **XNET WiFi devices**, it's crucial to conduct a thorough **site survey**. This will help you assess the environment, identify potential challenges, and determine the best locations for your access points (APs). **Site surveys** should include checking for **existing WiFi networks**, physical obstructions, and sources of interference. You can use tools like **Ekahau** or **NetSpot** to map out the site and identify optimal placement spots.

### Identifying and Gathering Necessary Tools and Materials

Proper planning includes ensuring you have all the necessary tools and materials. Depending on your specific installation, this could include:

- **Network Switches and Routers:** Determine if you need to install a switch or router, or if the existing network infrastructure will suffice. Having a cheap switch and power strip spare is highly recommended.
  - [Cheap 5 Port Gigabit Switch](https://amzn.to/3yBfHIx)
  - [Cheap and Great Surge Protector and Power Strip](https://amzn.to/4cwUrRV)
- **Drills and Mounting Equipment:** For mounting APs, especially in outdoor or high places, you'll need a drill, anchors, and brackets.
  - [Recommended Drill](https://amzn.to/471KMBJ)
    - [Recommended Drill Set](https://amzn.to/3yNxpIQ)
    - [Recommended Drill Bits](https://amzn.to/4dwfh55)
  - [Example Anchors](https://amzn.to/3yCQwFs)
  - [Example Mounting Brackets](https://amzn.to/3AAwaNK)
- **Ethernet Cables:** Use **Cat6 or Cat6a** Ethernet cables for optimal performance, especially if the run is longer than 100 feet. Always choose cables with proper shielding if you're running them in areas with high interference.
  - [Premade 100ft CAT 6A Ethernet Cable](https://amzn.to/4fPYRpT)
  - [Indoor Inwall CAT 6A Ethernet Spool](https://amzn.to/3yNxKeA)
  - [Outdoor Direct Burrial CAT 6A Ethernet Spool](https://amzn.to/46SGbBE)
- **RJ45 Connectors and Crimping Tools:** For custom-length cables, have connectors and a **crimping tool** ready.
> Learn [how to crimp ethernet cables](https://www.youtube.com/watch?v=y0V5XSn-H2g).
  - [CAT 6A Passthrough RJ45 Ethernet Connectors](https://amzn.to/3YQ2c28)
  - [Good Starter Ethernet Crimper](https://amzn.to/4fVkSUc)
  - [Ethernet Cable Tester](https://amzn.to/4dQMGat)
  - [PoE Tester](https://amzn.to/3yOLYMa)
- **Powerline or CoAX Adapters:** If direct Ethernet runs aren't possible, consider using **Ethernet over Powerline** or **CoAX adapters** as alternatives.
  - [Recommended Powerline Adapter](https://amzn.to/3McpFD1)
  - [Recommended COAX MoCA Adapter](https://amzn.to/3Mfy74C) 

### Picking the Installation Location and Identifying the Source of Internet Connection

Choosing the right installation location is critical. For **indoor installations**, aim to place APs in central locations with minimal obstructions. For **outdoor installations**, make sure the APs are elevated between **15-30 feet**, ensuring they are neither too high nor too low. Identify and secure the source of the internet connection beforehand, making sure it meets the bandwidth requirements for XNET.

### Refer to Manufacturer Installation Documentation

Before installing any **XNET WiFi devices**, it's essential to review the installation documentation provided by the manufacturer for each specific access point (AP). These guides offer critical information on proper setup, mounting, and configuration, ensuring that your installation is both efficient and compliant with the device's requirements. Below are links to the official installation guides for each AP model commonly used in XNET deployments:

- **XR560**:
  - [XR560 AP Quick Setup Guide](https://support.ruckuswireless.com/documents/4273-ruckus-r560-ap-quick-setup-guide/download)
  - [T-Bar Bracket Quick Setup Guide](https://support.ruckuswireless.com/documents/4807-ruckus-t-bar-bracket-quick-setup-guide/download)
  - [Stadium Enclosure Quick Setup Guide](https://support.ruckuswireless.com/documents/4400-stadium-enclosure-quick-setup-guide/download)
  
- **T350**:
  - [T350C AP Quick Setup Guide](https://support.ruckuswireless.com/documents/3721-ruckus-t350c-ap-quick-setup-guide-qsg/download)
  
- **XV2-2T0**:
  - [Enterprise Wi-Fi 6 Access Point Hardware and Installation Guide](https://www.cambiumnetworks.com/resource/enterprise-wi-fi-6-access-point_hardware-and-installation-guide-6-5-3/)
  
- **XP6 Pro**:
  - [AP6-Pro Quick Setup Guide](https://media.alta.inc/qsg/AP6-Pro_QSG.pdf)
  
- **XPX6**:
  - [AP6-Pro Outdoor Quick Start Guide](https://media.alta.inc/qsg/ap6-pro-outdoor/ap6-pro-outdoor-quick-start-guide.pdf)

By consulting these documents, you'll ensure that each AP is installed correctly, maximizing performance and longevity while minimizing potential issues during and after installation. These guides also provide manufacturer-specific tips that can save time and reduce errors in your deployment process.

______

## Installation Best Practices

### Indoor vs. Outdoor Installation Techniques

**Indoor Installation:** When installing APs indoors, focus on placing them in open areas away from walls and large metal objects that can block the signal. Ceiling or high wall installations are typically ideal. Ensure that the AP is positioned to cover the maximum area while avoiding interference from other devices.

**Outdoor Installation:** Outdoor APs should be mounted on poles or walls at a height of **15-30 feet**. This elevation is optimal for both signal propagation and security. Always ground your outdoor APs to protect them from electrical surges. Use a **lightning arrestor** if the area is prone to thunderstorms. Make sure the APs are weatherproofed and have proper environmental protection to withstand the elements.

### Grounding Your Outdoor Installation (Outdoor APs only)

**Grounding** is essential for protecting your outdoor APs from lightning strikes and electrical surges. Always use a grounding rod and connect it to the AP’s grounding terminal. Ensure that the grounding system meets the local **National Electrical Code (NEC)** standards. **Grounding** not only protects the hardware but also ensures the safety of the entire network setup.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/GLNuC7GcAcU?si=zgNnXSrqo-tqKWM0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Optimizing Placement of Indoor APs

For indoor installations, the placement of **XNET Access Points (APs)** is crucial to ensure optimal coverage and consistent network performance. Correct positioning can minimize dead zones, reduce interference, and maximize the number of connected devices.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_NMS4bs8_II?si=lujel879LxX3fnnI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### Central Location is Key

The most effective way to achieve broad coverage is by placing the AP in a **central location** relative to the area that needs coverage. This allows the signal to radiate outward evenly, covering all corners of the space. When choosing the central location, consider the layout of the space—whether it's an open office, a residential area, or a commercial venue—and ensure the AP is as equidistant as possible from the farthest points that need coverage.

#### Avoiding Physical Obstacles

**Physical obstacles** such as walls, floors, and large metal objects can significantly degrade the signal strength. Thick walls made of concrete or brick, as well as floors between levels, are particularly problematic as they can block or weaken the WiFi signal. To optimize signal propagation:

- **Keep the AP elevated:** Mount the AP on the ceiling or high on a wall to reduce interference from furniture and other low-level obstructions.
- **Minimize proximity to metal objects:** Metal can reflect and absorb WiFi signals, leading to poor performance. Place the AP away from large metal objects like filing cabinets, metal shelving, or large appliances.
- **Avoid corners:** Corners and tight spaces can trap and absorb the WiFi signal, reducing its reach. Place the AP in open areas to ensure the signal can spread effectively.

#### Choosing Between Omnidirectional and Directional Antennas

The type of antenna you use plays a significant role in how the WiFi signal is distributed throughout the space. 

> *XNET only offers Omni directional by default, if you want a directional varient you'll have to place a special order.*

- **Omnidirectional Antennas:** These antennas broadcast the signal in all directions equally, making them ideal for most general-purpose installations. They work best in open areas where coverage is needed across a broad area, such as open-plan offices, lobbies, or large rooms.
  
- **Directional Antennas:** If you need to focus the signal in a specific direction, such as down a long hallway or toward a specific section of a building, **directional antennas** are the better choice. These antennas concentrate the signal in a particular direction, providing stronger coverage in the desired area while minimizing interference in other directions.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/4rvI2_FD9H8?si=KjNF_idQZsgAEBD-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### Additional Tips for Optimal Placement

- **Height Matters:** For most indoor environments, the AP should be placed between 8 to 12 feet above the ground. This height is ideal for both minimizing interference from objects and maximizing coverage.
- **Consider User Density:** In areas with a high density of users, such as conference rooms or classrooms, it may be beneficial to use multiple APs spaced evenly to avoid overloading a single unit.
- **Test and Adjust:** After initial installation, use a WiFi analysis tool like **WiFiAnalyzer** to check the coverage and make adjustments as needed. Fine-tuning the position can significantly improve network performance.

By carefully considering these factors, you can optimize the placement of indoor APs to ensure reliable, high-performance WiFi coverage throughout the installation area.

### Brief Intro to Radio Line of Sight (LoS) vs. Actual Line of Sight

**Radio Line of Sight (LoS)** refers to the ideal path, within what is called a **Fresnel Zone**, that radio waves travel between two points, unobstructed by physical objects. However, **Actual Line of Sight** is what you see visually, which may include obstacles like trees, buildings, or terrain. Understanding the difference is important for optimizing signal strength, especially in outdoor installations.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/b7ey2upDhRw?si=5zwYST6o4EQt_8F6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Understanding the Squared Cube Law and Calculating Azimuth and Elevation

The **Squared Cube Law** explains that as you scale up a network, the area covered by the AP increases by the square of the distance, but the volume or capacity grows by the cube. This means you must carefully plan the number and placement of APs to avoid dead zones. Use tools like **Radio Mobile** to calculate the **azimuth and elevation** angles for your APs, ensuring optimal signal distribution.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/qoM17ikreio?si=2w5Kz_iTznXqy8r0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

______

## On-Site Security Considerations

You don't need to know what these are, but you need to be generally aware of if they exist on your network that you're installing them.

### Implementing VLANs and VRFs

**Virtual LANs (VLANs)** and **Virtual Routing and Forwarding (VRFs)** are essential for network segmentation and security. VLANs help isolate different types of traffic, such as guest and internal traffic, reducing the risk of cross-network contamination. **VRFs** provide an extra layer of security by allowing multiple routing tables to coexist on the same physical router.

### Utilizing DNS Sinkholing, IDS/IPS, and Threat Prevention

**DNS Sinkholing** is a technique used to redirect malicious traffic away from its intended destination, effectively neutralizing threats. Implementing **Intrusion Detection Systems (IDS)** and **Intrusion Prevention Systems (IPS)** will help you monitor and block suspicious activity on the network. Always have **threat prevention mechanisms** in place to safeguard against potential cyberattacks.

______

## Post-Installation Checks

### Testing Network Coverage and Performance

After installing the XNET devices, it’s crucial to test the network coverage and performance to ensure everything is functioning as expected. Tools like [**WiFiAnalyzer**](https://play.google.com/store/apps/details?id=com.vrem.wifianalyzer&hl=en) or [**WiFiMan**](https://apps.apple.com/us/app/wifiman/id1546870274) can help you verify the signal strength and identify potential dead spots. Look for 1-2 SSIDs with "XNET" in the name to confirm that the APs are broadcasting correctly.

### Troubleshooting Common Issues

Some common issues you may encounter include **interference from other devices**, **weak signal strength**, or **connectivity drops**. To troubleshoot:

- **Reposition APs:** If the signal is weak, try moving the AP to a higher or more central location and/or adjust where the antenna is aiming.
- **Check Cabling:** Ensure all cables are properly connected and that there are no breaks or damages.
- **Check for the XNET SSID**: If any XNET ssid shows up in your wifi list, the device is working. Otherwise, contact XNET Support.

### Checking all passthrough holes have been properly sealed and are water resistant. (Outdoor APs only)

Ideally you'll use a combination of gafter tape, caulking, conduit, and foam to make a air and water tight seal on all openings that go indoor to outdoor or outdoor to indoor in any way. You should check these at least yearly.
______

## Conclusion

Installing **XNET WiFi devices** requires careful planning, precise execution, and a strong understanding of both indoor and outdoor networking environments. By following the steps outlined in this guide—from **verifying AP operation before installation day** to **post-installation checks**—you can ensure that your installations are successful and provide optimal coverage. Always prioritize **security** and **proper grounding** in your installations to protect both the hardware and the network.

______

## References

- [WiFiAnalyzer - Android WiFi Tool](https://play.google.com/store/apps/details?id=com.vrem.wifianalyzer&hl=en)
- [WiFiMan - iOS WiFi Tool](https://apps.apple.com/us/app/wifiman/id1546870274)
- [XNET Discord - Support and Troubleshooting](https://discord.gg/xnetmobile)
