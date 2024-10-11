# XNET WiFi Deployer Guidelines

## Purpose:

The XNET WiFi Deployer Guidelines aim to create a clear, repeatable process for ensuring quality data offload from deployers without harming the XNET network. These rules ensure that deployers maintain the expected performance standards for their networks, while internal processes ensure XNET can respond quickly to any harmful activity.

1. **Onboarding Process**
- **Application Submission**: Deployer must submit an application on XNET's website and provide complete and accurate information about the deployment site. 
- **Site Verification**: XNET independently verifies and confirms registered AP locations for offload compatibility. XNET does not allow deployment in residential areas, as only commercial and public locations are suitable for carrier offload. 
- **Access Point Requirements**: Only Passpoint-compliant Wi-Fi 6, 6E, or 7 access points from supported manufacturers will be accepted onto the XNET network. A list of supported models is displayed at registration. Other models may still be submitted if they meet these characteristics, but XNET reserves the right to validate these models and decide if they are to be approved and registered. All access points must have the latest firmware installed at the time of onboarding. Upon detection, non-compliant access points from unsupported vendors will be banned from the network without notice. 
- **Support**: Deployers should review documentation on XNET Docs, and on relevant Discord channels prior to contacting XNET for deployment support. Deployers should also be sufficiently knowledgeable to troubleshoot their deployment hardware and backhaul/networking configurations.
-** Carrier Approval**: Once all steps are complete and the devices are validated for compliance with XNET requirements, deployers undergo a qualification period where their access points are submitted for carrier approval.  

2. **Initial Qualification And Carrier Approval Period**
- **Initial Qualification**: in many cases APs can start offloading carrier traffic within several days after initial location validation. However, in some cases it could take a few weeks for carriers to begin offloading. This process is outside of XNET’s control as carriers use specific location validation and traffic steering tools to determine suitability for offload according to their own policies.   
- **Performance Evaluation**: Upon approval, XNET starts evaluating traffic metrics, such as the number of unique devices connected, session duration, data offload amounts, and rejected session attempts, among other relevant indicators. This evaluation is tailored to ensure deployments meet XNET and partner carriers’ QoS targets.
- **Feedback & Adjustment**: If abnormal metrics are detected, deployers will receive improvement feedback and advice for optimizing traffic performance. Approval is not guaranteed until a location is fully optimized and validated for production offload.

3. **Performance Assessment Phase**
- **Prolonged Observation**: Following the initial approval and qualification period, the deployer enters a performance observation phase that can last 1-2 epochs, depending on the deployment area size and AP count.
- **Defining Benchmarks**: XNET establishes performance benchmarks for different location types, by analyzing offload traffic. Metrics include the number of connected devices, sessions, and total data transferred, used to define average traffic patterns.
- **Support During Assessment Phase**: XNET will assist deployers in addressing unusual traffic patterns e.g. due to unintentional misconfiguration. However, due to strict quality requirements by our customers, persistent abnormal traffic can also result in temporary suspension of traffic processing and termination of payout. 

!!! Note
    In cases of confirmed or attempted manipulation of traffic patterns, a lifetime ban will be imposed on all APs operated by the deployer.

4. **Outlier Detection & Abnormal Traffic**
- **Outlier Investigation**: XNET uses specific tools to detect and investigate traffic patterns that deviate significantly from normal performance (e.g., unusually high offload volume from a low device count, abnormal session durations, etc.).
- **Information Requests**: XNET contacts deployers to verify traffic data and provide performance improvement suggestions.
- **Unforeseen Emergencies**: For natural disasters/acts of god/terrorism events such as hurricanes, tornadoes, shootings, and flooding, abnormal traffic patterns are expected that deviate from non-disaster locations and as long as the AP owner communicates this in advance with a ticket XNET will be able to flag their unit as affected and as long as traffic returns to normal once the event passes XNET will intend to keep affected AP’s running as normal with payouts uninterrupted.

5. **Offboarding Process for Non-Compliant Deployers**
- **Final Support Attempt**: Deployers who fail to normalize abnormal traffic after receiving support will receive a final notice to rectify performance.
- **Termination of Payments**: If traffic remains abnormal, deployers will be removed from the payout structure.
- **Deactivation of APs**: In extreme cases, deployers' access points will be deactivated within 24 hours to prevent harm to XNET’s network.
- **Closure**: In severe cases, deployer accounts may be closed. Any remaining earnings will be settled according to the terms of the agreement.

6. **Reporting & Appeals**
- **Incident Reporting**: Deployers may report incidents (e.g., local events) that led to abnormal traffic patterns.
- **Appeal Process**: Deployers may appeal offboarding decisions within 30 days by providing additional evidence or requesting a traffic reevaluation.
- **Responsible Parties**: XNET’s fraud team, based on analytics data, will make suspension and banning decisions, and support will communicate with deployers throughout the process.
