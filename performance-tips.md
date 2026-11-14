# Browser Performance & FPS Tips

Because GeoFS runs entirely in your web browser using WebGL and Cesium 3D terrain streaming, performance depends heavily on your browser settings and graphics configuration. Use the tips below to boost frame rates (FPS) and reduce stuttering.

---

# 1. In-Game Graphics Settings

Open the **Options** menu on the bottom bar in GeoFS and adjust the following settings:

* **Graphics Quality:** Set to **Low** or **Medium** if your frame rate drops below 30 FPS, especially around dense cities or large airports.
* **Anti-Aliasing:** Disable this option on laptops or integrated graphics cards—it smooths jagged edges at the cost of heavy GPU load.
* **Shadows:** Turn off **Shadows** (or set to Low) for an immediate 10–20 FPS boost on older hardware.
* **Resolution / Pixel Ratio:** Lowering the internal resolution scale reduces GPU workload significantly without hurting gameplay.
* **Multiplayer Traffic:** If large multiplayer hubs cause lag spikes, hide multiplayer labels or switch to a less crowded server.

---

# 2. Browser & Hardware Acceleration

GeoFS requires your dedicated GPU (or integrated graphics hardware) rather than software rendering.

* **Enable Hardware Acceleration:**
  * **Chrome:** Go to `chrome://settings/system` and ensure **Use graphics acceleration when available** is turned **ON**, then restart Chrome.
  * **Edge:** Go to `edge://settings/system` and ensure **Use hardware acceleration when available** is turned **ON**, then restart Edge.
* **Close Background Tabs:** Streaming video (YouTube, Twitch) or having dozens of open tabs competes for RAM and GPU memory.
* **Plug In Your Laptop:** Most laptops throttle GPU performance when running on battery power.

---

# 3. Add-on & Script Optimization

* **Limit Heavy Scripts:** Running multiple weather, traffic, or custom terrain scripts simultaneously increases CPU usage. Disable any Tampermonkey scripts you aren't actively using for that flight.
* **GeoFS Pro (HD) Impact:** Higher-resolution satellite tiles require more bandwidth and video memory. If terrain tiles load slowly or cause stutters, temporarily disable HD terrain forcing over slow connections.

---

<div align="center">
  <a href="README.md">&larr; Back to Table of Contents</a>
</div>
