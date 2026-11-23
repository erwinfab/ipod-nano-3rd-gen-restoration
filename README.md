# Apple iPod Nano 3rd Gen (Model A1236) — Hardware Restoration & Micro-Soldering

Hardware teardown, micro-soldering battery replacement, and LCD fault isolation on an Apple iPod Nano 3rd Generation (A1236).

## Tools & Components
* **Soldering & Rework:** 80W soldering station (330°C–350°C), fine conical tip, 0.8mm flux-core solder wire, paste flux, desoldering copper wick, 90%+ isopropyl alcohol
* **Replacement Parts:** Li-ion replacement battery ribbon assembly, replacement internal LCD panel (A1236)

---

## Part 1: Teardown, Power Rail Diagnostics & Micro-Solder Battery Replacement
1. **Chassis Teardown:** Opened the rear stainless steel housing carefully to expose the logic board and battery assembly without stressing perimeter clips.
2. **Desoldering & Pad Prep:** Removed the degraded factory battery ribbon, applied paste flux, and used desoldering braid to clear a solder bridge between adjacent contact pads while keeping all three copper pads intact on the substrate.
3. **Battery Reflow:** Aligned the new battery flex cable over the three board eyelets, anchored the center pad first to lock alignment, and soldered the outer positive/negative leads cleanly.
4. **Board Verification:** Confirmed logic board power-up, storage spin-up, and click-wheel audio response prior to final reassembly.

![Logic Board Pad Prep and Battery Reflow](assets/01-board-pad-cleanup.jpg)

---

## Part 2: Display Fault Isolation, LCD Replacement & Verification
1. **Fault Isolation:** During initial power-on testing, the device booted and responded to controls, while the display showed a white backlight with dark liquid-crystal bleed along the right edge. Re-seating the display ZIF ribbon confirmed the logic board connector was intact and isolated the fault to an internal LCD glass fracture.
2. **LCD Replacement:** Unlatched the display ZIF connector, removed the fractured inner LCD panel, seated the replacement display assembly straight into the connector, and locked the retention tab.
3. **Final Verification:** Verified full UI rendering, backlight uniformity, click-wheel navigation, and battery charging.

![Final Restored iPod Nano](assets/04-final-working-build.jpg)

---

## Repair Walkthrough Video
> *Video demonstration currently being edited — process stills above show the completed board rework and final verification.*
