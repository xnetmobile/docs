# XNET WiFi Deployer Management Process

**Revision:** 1.00  
**Date:** October 10th, 2024  

## Goal
The goal of this process is to create a fair, repeatable and logical process to handle deployers offloading data with traffic patterns that may or do harm the XNET network. XNET must constantly monitor data offload quality to protect its network and the carrier's networks. XNET treats every partner and deployer as neutral when initially onboarded and any action taken is based on clear and overwhelming data that abnormal traffic patterns are present and if they cannot be resolved after attempting to work in good faith, removing that traffic from XNET’s network. For exceptional cases such as compromised networks or networks attacking XNET, XNET can and will take emergency immediate action to protect the offload network.

1. **Onboarding Process**
- **Application Submission**: Deployer submits an application to participate in the WiFi offload program at [XNET Activation portal](https://activate.xnet.company/). 
- **Site Verification**: XNET will verify the deployer’s WiFi access point locations to ensure compatibility with offload requirements.
- **Technical Requirements**: Deployer’s equipment is reviewed for compliance with the program's technical standards (bandwidth, security, offload capabilities). Review [Acceptable Use](https://docs.xnet.company/acceptable_use/)
- **Hardware Updates**: The deployer is expected to always have the most recent production firmware on all wifi infrastructure within 30 days of release and have secure management and control of their APs and other local infrastructure security. If an AP is physically moved to a new location, a new registration should be submitted in order to continue using it with XNET’s carrier offload. XNET reserves the right to suspend APs with outdated firmware from the network without notice, if they are causing network performance or accounting errors. XNET will terminate traffic  processing and  reward payouts for such APs on the day of suspension.
- **Training & Support**: Deployers are expected to review all documentation in this site and, if needed, take appropriate training or pay for wifi site survey resources for optimizing WiFi for offload and be knowledgeable on troubleshooting common issues with their hardware.
Dashboard Setup: Deployer is given access to a dashboard to monitor sites and, in the future, will also be able to manage their fleet and its performance, earnings, and traffic data.
- **Approval**: Upon completion of this onboarding process, the deployer is approved for the 1 epoch qualification period where their AP’s and/or sites are sent to the carriers for approval.

2. **Two Epoch Qualification Period**
- **Initial Monitoring**: XNET reserves the right to have deployers undergo a two epoch monitoring period where their traffic patterns including sessions and data offload amounts are tracked. No guarantee of approval is implied during this period.
- **Performance Evaluation**: At the end of the qualification period, the deployer’s traffic is evaluated based on different indicators such as:
    - Number of devices connected
    - Number of sessions initiated and sustained
    - Amount of data offloaded
    - Rejected session attempts
- **Feedback & Adjustment**: If performance metrics are abnormal, the deployer is contacted for feedback and advice is provided on optimizing traffic flow and network performance.

3. **Baseline Period**
- **Extended Monitoring**: After the initial qualification period, the deployer enters a baseline period of 1-2 epochs, depending on the location type and number of APs installed, for further performance monitoring.
- **Establishing Norms**: A baseline is established using statistical averages of traffic data from all deployers. Metrics such as the number of phones, sessions, and data transferred are used to define normal traffic behavior.
- **Support Interventions**: XNET has seen many unusual traffic patterns emerge as the result of misconfigured or overloaded equipment. If these problems are detected, we will work with the deployer to resolve them. If the deployer and XNET cannot resolve the issue in good faith (defined as XNET recommending changes and those changes being partially or fully implemented to resolve the issue in a reasonable amount of time), XNET will be forced to suspend the processing and payout from traffic. XNET reserves a lifetime ban for extreme situations onto any deployer or AP’s or Sites XNET determines are intentionally harming the XNET offload processing. XNET may lift or revise a lifetime ban if new data becomes available or the deployer and XNET agree to a new onboarding with the issues resolved in good faith.

4. **Outlier Detection & Abnormal Traffic**
- **Statistical Outliers**: XNET will investigate any traffic pattern that represents a major deviation from typical offload performance KPIs. Abnormal traffic could include:
Low User Count With High Offload Volume: small number of same devices generating large offload volume in a short period of time. 
- **High Device Count**: comparatively significant increase in number of mobile devices connecting in a given location
- **Session Abnormalities**: very short or excessively long connectivity sessions compared to normal traffic patterns in the same location.
- **Connectivity Record Errors**: this could include connectivity and accounting record errors (e.g. 1TB of data transferred in 1 second, 90%+ rejection rate etc.) due to local network configuration errors, local firewalls etc. 
This list is not extensive but is meant to provide high level guidance.
- **Communication**: Deployer is contacted to verify the location and traffic data. Suggestions for performance improvement are given, and they are provided with troubleshooting support.

5. **Offboarding Process for Non-Compliant Deployers**
- **Final Support Attempt**: If the deployer's traffic remains abnormal (0.3% outlier) after working with the support team and following guidance, they will be given a final notice to rectify their performance.
- **Termination of Payments**: If the traffic cannot be brought within expected norms (within 99.7% of expected traffic behavior), the deployer may be removed from the payout structure.
- **Deactivation of Access Points**: In severe cases, the deployer’s WiFi access point(s) may be deactivated from the offload system in <24 hours, preventing further abnormal traffic from harming XNET’s network.
- **Closure**: The deployer’s account may be closed at XNET’s discretion for extreme cases, and any remaining earnings from normal data transfer (if eligible) are settled as per the terms of the agreement.

6. **Payouts & Data Calculations**
- **Site Rewards Qualification Timeline**: XNET sends regular updates to carriers regarding newly-qualified locations, however a carrier can adopt all/some/none of the locations we share with them. This timeline for qualification is at the discretion of the carrier and on average can take anywhere from a few days to a few weeks before the site and radios are accepted for data offload. Deployers should not expect the day they register a site or radios as a start date for accruing rewards.    
- **Rewards Payouts**: Should all radios at a given deployments site operate and adhere in accordance with the guidelines outlined above payouts will be distributed within the network's existing epoch distribution schedule (About every 2 weeks + processing time for rewards calculations).
- **Data Calculations**: Data calculations are summarized and calculated in accordance with what the carriers have approved and accepted as payable data offload. Deployers should NOT base data offload earning calculation from their managed equipment or dashboards (Ex. Managed routers, radio offload reports or other data offload management tools).
- **Payout Delays & Witholdings**: If a deployment site's radios are under extended performance review, indicating abnormal traffic, or not adhering to our performance guideline in any way, they may be subject to payment delays or withholding until all issues are resolved.
- **Claiming & Viewing Offload Rewards**: At the end of each epoch a public summarized ledger for data offload rewards is published to the community. Deployers can view new data offload reports once it's announced in our public “Token Ledger” discord channel. The “Radio Reward Tokens by Epoch Sheet” can always be viewed at any time under the [Data Rewards - Dispersal] tab within this sheet.
- **Rewards disputes**: Should a deployer need to inquire about a reward payout distribution or dispute an issue about rewards of any kind, deployers must open a ticket within the “Open A Ticket” channel on our Public Discord. Please choose the “Open A General Ticket” option when submitting your rewards ticket.                   

7. **Reporting & Appeals**
- **Incident Reporting**: Deployers may report any unforeseen incidents that may have caused abnormal traffic (e.g., local events, outages, etc.).
- **Appeal Process**: Deployers can appeal the offboarding decision within 30 days of a suspension or banning by providing additional evidence or requesting a reevaluation of their traffic patterns once they believe it is within norms due to changes in their infrastructure configuration.
- **Responsible Parties**: XNET suspension, banning, and appeals are at the written direction of XNET’s fraud team  based on the data provided by the XNET analytics team members and XNET’s business partners. XNET support will communicate directly with deployers and bring in responsible parties if escalation is needed. 
