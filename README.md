**Hike Safety System**


   **Introduction**
 

  Safety System developed by Lora Ops (CSM). The main purpose of safety tools is for the hiker and even for SAR applications. This system is cheap, simple, and efficient. Beside it use for hiking, HSS can be applied to outdoor activity, tactical or field operation with its ability to operate on offgrid area within a 10 km+ range up to 20km (No Barricade).

  **Methods**

  HSS uses the LoRa Module on 433Mhz frequency and ESP32/S3 as the main microcontroller.

V1HSS. It uses our phone as a secondary device; ESP32 via BLE will communicate with the phone and grab the phone's GPS, BAT, and send it to other devices via meshtactics. If the phone malfunctions or is unusable, this system has another backup; it will use LoRa to ping other devices, then it will process based on signal strength/BoT,EoT, and the triangulation system. (Legacy HSS and Available)

  V2.HSS. Or HSS+, a very advanced system that uses TAK (Team Awareness Kit) Integration and combines with Meshtactics. This system has just been upgraded to a geospatial mapping and situational awareness application. It allows users to share their GPS location precision via phone or integrated within the HSS Module (HSS03), users can place destination, markers, hazard on map and can be seen to other users on realtime. The same system that Law Enforcement uses, except this one is off-grid and doesn’t need any communication satellite or complex network system; the network moves with this system also cheap. (New Gen HSS, in development. Available Limited)





**   This Repository Doesn't share any HSS Source Code or Diagram, it just an archieve.**
