

<h1 align="center">Smart Home Configuration</h1>
<h3 align="center">Home Assistant Configuration and Documentation for my Smart Home.</h3>
<h4 align="center">Feel Free to :star: my repo to show me some love :grin:<br>
Additionally, contact me:
<img src="https://img.shields.io/twitter/follow/perksie?style=social"/></h4><br>
<p align="center">
<img src="https://img.shields.io/maintenance/yes/2021"/>
<img src="https://img.shields.io/github/commit-activity/m/perksie/Home-Assistant"/>
<img src="https://img.shields.io/badge/HA--Version-2021.2.3-brightgreen.svg"/>
</p>
<p align="center">
This is my smart home. A continuous work in progress I'm sure you can all relate to. To Begin, the following methods of automation have been through a criterion of integration. This criterion is:</p>
<p align="center">
<b>
- Must have local control and not rely on cloud integration.<br>
- Must be family friendly</b><br></p>

<p align="center">Without meeting the criteria, it won't make it into household 'production'.</p>

<p align="center">To further explain this criteria:<br></p>
<i>Must have local control</i><br>
<p>I'm sure most of us Home Assistant users can agree that relying on our devices to work on an internet connection can seem a bit daunting. Plus the added latency for a command to bounce around the world to change the light bulb you are sitting under seems a little silly don't you think?<br>
<b>Most importantly,</b> relying on someone/an organisation to hope that the code is secure enough really scares me. The publicity around unsecured IoT devices rings true. Please believe it.</p><br>
<i> Must be family friendly </i><br>
<p> I don't live alone. Home automation needs to better our lives at best by still remaining functional and speedy. I don't expect my family members to whip out their phones and open the app to turn the light on when there is a switch that does it way quicker with the same outcome. I try to look for ways to automate that process. For example, a motion sensor will turn the light on if after 5PM.</p> <br>

<p align="center">
|<a href="https://github.com/perksie/Home-Assistant#network-topology">[Network Topology]</a> | <a href="https://github.com/perksie/Home-Assistant#hardware">[Hardware]</a> | <a href="https://github.com/perksie/Home-Assistant#lighting">[Lighting]</a> | <a href="https://github.com/perksie/Home-Assistant#security">[Security]</a>
</p>
<br>

#### Lighting <a name="lighting" href="https://github.com/perksie/Home-Assistant#lighting"></a>

<table style="undefined;table-layout: fixed; width: 562px">
<thead>
  <tr>
    <th>Device</th>
    <th>Quantity</th>
    <th>Connection</th>
    <th>Notes</th>
  </tr>
</thead>
<tbody>
<tr>
<td><a href="https://yeelight.net.au/products/xiaomi-yeelight-smart-led-wifi-tune-able-colour-bulb"target="_blank" rel="noopener noreferrer">Yeelight RGB Bulbs</a><br>
<img src="https://github.com/perksie/Home-Assistant/blob/master/img/lighting_system/yeelightrgb.jpg?raw=true" width="400" height ="180"></td>
<td>4</td>
<td>Wi-Fi</td>
<td>I bought the earlier versions of the depicted model here for about $15 AUD at the time. Blown away by how well these shine! Would probably buy these at today's prices.</td>
</tr>
<tr>
<td><a href="https://yeelight.net.au/products/yeelight-lightstrip-1s-2m"target="_blank" rel="noopener noreferrer">Yeelight RGB Strip</a><br>
<img src="https://github.com/perksie/Home-Assistant/blob/master/img/lighting_system/yeelightstrip.jpg?raw=true" width="400" height ="180"></td>
<td>1</td>
<td>Wi-Fi</td>
<td>These were a disappointing purchase. Not enough LEDs.</td>
</tr>
<tr>
<td><a href="https://www.aliexpress.com/item/4001331197520.html?spm=a2g0o.productlist.0.0.288d3e9dOPkaGb&algo_pvid=bff3a314-4288-43be-836b-ee079f92b092&algo_exp_id=bff3a314-4288-43be-836b-ee079f92b092-5&pdp_ext_f=%7B%22sku_id%22%3A%2212000024133823733%22%7D"target="_blank" rel="noopener noreferrer">WS2811 Strip</a><br>
<img src="https://github.com/perksie/Home-Assistant/blob/master/img/lighting_system/ws2811.jpg?raw=true" width="400" height ="180"></td>
<td>4+</td>
<td>Wi-Fi</td>
<td>Going forward, these are my goto for LED strips</td>
</tr>
</tbody>
</table>
<br>

#### Security <a name="security" href="https://github.com/perksie/Home-Assistant#security"></a>

<table style="undefined;table-layout: fixed; width: 562px">
<thead>
  <tr>
    <th>Device</th>
    <th>Quantity</th>
    <th>Connection</th>
    <th>Notes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><a href="https://konnected.io/products/konnected-alarm-panel-pro-12-zone-kit" target="_blank" rel="noopener noreferrer">Konnected Pro (12 Zones)</a><br>
    <img src="https://github.com/perksie/Home-Assistant/blob/master/img/alarm_system/konnectedpro.jpg?raw=true" width="300" height ="180"></td>
    <td>1</td>
    <td>Ethernet (PoE)</td>
    <td>So far this has been great</td>
  </tr>
  <tr>
    <td><a href="https://commerce.boschsecurity.com/au/en/Blue-Line-Gen2-PIR-Motion-Detectors/p/2602384139/" target="_blank" rel="noopener noreferrer">Bosch Blue Line Gen 2 Pet Friendly Motion Detector</a><br>
    <img src="https://github.com/perksie/Home-Assistant/blob/master/img/alarm_system/motionsensor.jpg?raw=true" width="165" height="180"></td>
    <td>2</td>
    <td>Hardwired to Konnected Pro</td>
    <td>Perfect for house pets that don't trip the alarm</td>
  </tr>
</tbody>
</table>

<br>
<h3 align="center">:construction: Work in progress :construction:</h3>
