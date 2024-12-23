
# Deployments

XNET nodes can be deployed by whoever has the means and access to good locations. The CBRS nodes require the use of a separate Gateway + radio in order to provide receive/transmit function, XNET network core function, spectrum access, and a blockchain function. The XNET Wi-Fi Offload nodes can operate in a standalone fashion and require no dedicated gateway. 

The choice of which to deploy depends on your location and proximity to high traffic areas. 

!!! info
    **XNET Hardware**: Visit [Datasheets](/tech/datasheet/) or the [XNET Shop](https://shop.xnet.company) to learn about supported hardware.

## CBRS

CBRS, through its use of dedicated wireless spectrum assignments, higher transmit power and LTE/5G network protocol offer can reach greater distances and carry high value services like phone number support, Voice and e-911, all of which XNET can support with its 3GPP certified core. 

!!! info 
    XNET CBRS nodes must coordinate with a managed Spectrum Access System in order to operate. CBRS nodes must register with XNET to provide information like location, height and orientation. 

<p style="text-align: center;">
  <a href="/img/overview/park.png" data-fancybox="gallery">
    <img src="/img/overview/park.png" alt="Park" style="width: 500px;" />
  </a>
  <br />
  <span style="font-size: smaller; color: gray;">A well placed rooftop CBRS node can cover a busy urban park.</span>
</p>


## Wi-Fi 

XNET uses Wi-Fi Passpoint, also known as Hotspot 2.0, to ensure that mobile devices automatically connect to the XNET Wi-Fi node. This valuable service reduces demand  on large cellular networks. While XNET does not generally prohibit Wi-Fi deployments in residential areas, these are only beneficial if targeting specific public places e.g., community gyms, pools, large lobbies, etc., or immediate vicinity outside, e.g., nearby bus stops, shops, etc.

!!! info 
    XNET Carrier Offload refers to the use of Wi-Fi networks to handle data traffic that would otherwise burden cellular networks. This technology is crucial for carriers in densely populated areas where mobile data traffic often exceeds network capacity.

<p style="text-align: center;">
  <a href="/img/overview/cafe.png" data-fancybox="gallery">
    <img src="/img/overview/cafe.png" alt="Park" style="width: 500px;" />
  </a>
  <br />
  <span style="font-size: smaller; color: gray;">An intimate cafe is a good place for XNET Wi-Fi.</span>
</p>
  


## Deployment Tips


**Wi-Fi**

Not all locations are created equal, especially when it comes to maximizing XNET Wi-Fi earnings. 

!!! tip 
    Mobile operators will not use or pay for Wi-Fi offload inside houses and apartments! These locations will be flagged and no rewards will be earned from such deployments.

**The best locations** are where people congregate and consume data on their phones: 

- **Airports:** Constant influx of travelers needing quick access to data.
- **Cafes and Coffee Shops:** Popular with both local and visiting patrons who often stay for extended periods.
- **Public Parks:** Increasingly equipped with Wi-Fi for public use, especially in urban areas.
- **Shopping Malls:** Large numbers of visitors with high smartphone usage.
- **Public Transit Stations:** Subways, train stations, and bus terminals where people use downtime to browse the internet.


**Poor locations** will not earn rewards because there is no offload potential: 

- Single Family Residential Areas.
- Rural Locations.
- Industrial Zones.
- Private Offices.
- Areas with Low Pedestrian Traffic.


**CBRS**

XNET CBRS nodes can only earn `$XNET` tokens if deployed in certain regions called clusters, designated by colored hexes. 

The [XNET Explorer](https://explorer.xnetmobile.com/) uses [XNET’s X5 Hex Grid](https://github.com/xnet-mobile/geometry) to divide the map into hexes defined by latitude and longitude. Each hex is about 1.8 km2 in area, and is uniquely identified by a 32 bit number and a corresponding three-word name.  Only CBRS radios operating in the permitted coverage area are eligible for rewards.

There are currently two types of priority rewards hexes, Silver and Gold. Radios deployed within priority reward hexes can earn significantly higher rewards than radios deployed in normal priority hexes.

!!! tip
    Geographic restrictions only apply to CBRS radio deployments which require tight clustering to provide the greatest value for LTE/5G offload partners. 

<p style="text-align: center;">
  <a href="/img/overview/hexes.png" data-fancybox="gallery">
    <img src="/img/overview/hexes.png" alt="NYC" style="width: 300px;" />
  </a>
  <br />
  <span style="font-size: smaller; color: gray;">New York City showing both silver and gold hexes.</span>
</p>