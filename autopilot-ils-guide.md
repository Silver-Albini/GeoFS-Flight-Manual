### **Autopilot & ILS Landing Guide**

The built-in Autopilot in GeoFS allows you to hold altitude, speed, heading, and execute automated Instrument Landing System (ILS) approaches on equipped runways.

---

### **1. Autopilot Controls Overview**

You can open the Autopilot panel from the bottom interface bar or toggle it with `A`.

* **SPD (Speed):** Holds your target airspeed in knots (kts) using automatic throttle control.
* **HDG (Heading):** Steers the aircraft to a compass heading (000° to 360°).
* **ALT (Altitude):** Climbs or descends to the target altitude in feet (ft).
* **V/S (Vertical Speed):** Controls how fast you climb or descend in feet per minute (fpm). Positive values climb; negative values descend.
* **NAV (Navigation):** Follows the active flight plan route or locks onto a selected runway's ILS localizer and glideslope.

---

# 2. Basic Cruise Setup

1. Take off manually and climb to at least **1,000 ft** above ground level.
2. Retract your landing gear (`G`) and flaps (`[`).
3. Set your desired **Altitude** (e.g., `30000` ft for airliners, `8000` ft for small props).
4. Set a reasonable **Vertical Speed** (e.g., `1800` to `2500` fpm for jets, `500` to `800` fpm for props).
5. Set your target **Speed** in knots and select a **Heading**.
6. Press `A` (or click ***AUTOPILOT***) to engage the Autopilot.

---

# 3. Step-by-Step ILS Landing

An ILS approach guides your aircraft automatically down to the runway threshold, both horizontally (localizer) and vertically (glideslope).

1. **Open the Navigation Map:** Click **NAV** on the bottom bar to locate your destination airport.
2. **Select an ILS Runway:** Click on the airport icon and pick a runway that displays a green ILS feather/cone extending from the runway threshold. Click **Set as destination** (or select the ILS frequency/runway directly).
3. **Line Up at the Right Altitude:** Position yourself roughly **10 to 15 nautical miles** out from the runway, aligned within 30° of the runway heading, at around **2,500 to 3,000 ft** above airport elevation. *(If you are too high, the aircraft will fly over the glideslope and fail to capture it.)*
4. **Switch to NAV Mode:** On the Autopilot panel, switch from `HDG` to **NAV** mode. The aircraft will turn to align with the runway centerline and automatically begin descending once it intercepts the glideslope.
5. **Configure for Landing:**
   * Reduce **SPD** gradually toward your aircraft's approach speed (typically **135–150 kts** for airliners).
   * Extend flaps in stages (`]` or `F`) as your speed drops.
   * Lower the landing gear (`G`) at around **1,500–2,000 ft** above the runway.
6. **Touchdown:** At around **100–200 ft** above the runway, press `A` to disconnect the Autopilot, flare slightly (pull gently back on the stick/arrow key), cut throttle to `0`, and apply wheel brakes (`Spacebar`) and thrust reversers (`R`) upon touchdown.

---

# Troubleshooting Common ILS Issues

* **Aircraft flies past the runway without descending:** You approached the runway too high or too fast, missing the glideslope beam from above. Always capture the glideslope from *below* (around 2,500–3,000 ft AGL).
* **Aircraft oscillates left and right aggressively:** Your airspeed is too high for the final turn, or time compression is active. Keep simulation speed at `1x` during approaches.

---

<div align="center">
  <sub>GeoFS Flight Manual &bull; Maintained by Silver-Albini</sub><br>
  <sub>Not officially affiliated with GeoFS.</sub>
</div>
