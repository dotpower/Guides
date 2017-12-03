## LITEBEAM 5AC GEN2 - "WIRELESS"
* **Basic Wireless Settings**
   * WIRELESS MODE: 
   ```ssh
   Station PtMP
   ```
   * SSID: 
   ```ssh
   Det sendepunkt man forbinder til, f.eks. www.kolinds.net_KOL2_C_P4_N for Nord panelet på møllen.
   Vi besluttede på sidste møde at undlade www. fremadrettet, dette er dog ikke blevet ændret endnu.
   ```
   * LOCK TO MAC: 
   ```ssh
   Denne funktion bliver aktiveret, hvis man trykker på "Select" ud for SSID, og vælger et sendepunkt, og så trykker på "LOCK TO AP" i bunden. Dette låser så bruger radioen kun kan connecte til denne specifikke MAC adresse, og skal ændres eller slettes ved udskiftning af radio i sendepunkt. Bør ikke anvendes. 
   ```
   * CHANNEL WIDTH: 
   ```ssh
   Auto 20/40 MHz
   ```
   * AUTO CHANNEL WIDTH: 
   ```ssh
   OFF
   ```
   * CONTROL FREQUENCY SCAN LIST, MHz: 
   ```ssh
   OFF
   ```
   * ANTENNA: 
   ```ssh
   23 - 23 dBi
   ```
   * CALCULATE EIRP LIMIT: 
   ```ssh
   Skal stå til "OFF" og så indstilles Output power, som er næste punkt. Hvis den stilles til "ON" Så kører den auto, og det kan muligvis være ustabilt.
   ```
   * OUTPUT POWER: 
   ```ssh
   Indstilles manuelt til vi ligger på ca. 50-55 dBm. Alt under 40 dBm er for hot, og kan forringe sendepunkets kvalitet, og forbindelser over 70 dBm vil være for dårlige. 
   ```
   * AUTO ADJUST DISTANCE: 
   ```ssh
   ON
   ```
   * DISTANCE: 
   ```ssh
   Kører auto pga. sidste punkt.
   ```
   * MAX TX DATA RATE: 
   ```ssh
   Auto
   ```
   * DATA RATE MODULE: 
   ```ssh
   Default
   ```
* **Wireless Security** 
   * SECURITY: 
   ```ssh
   WPA2-AES
   ```
   * WPA AUTHENTICATION: 
   ```ssh
   PSK
   ```
   * WPA PRESHARED KEY: 
   ```ssh
   Key@kol1ind (Husk stort K i Key)
   ```
* **Secondary SSID**   
   * Denne funktion er disabled *
      ```ssh
      ```
* **Advanced** 
   * AMPDU:
   ```ssh
   32
   ```
   * AMSDU:
   ```ssh
   ON
   ```
   * Sensitivity Treshold:
   ```ssh
   OFF
   ```
   * Automatic Powercontrol:
   ```ssh
   ON
   ```
   ## LITEBEAM 5AC GEN2 - "NETWORK"
* **Network Role**
   * Network Mode: 
   ```ssh
   Router
   ```
* **Configuration Mode**
   * Configuration Mode: 
   ```ssh
   Simple
   ```
   
   
   
   
 
