# Aircraft-Tracking-with-Hackrf-one-and-python

An SDR project on macOS using HackRF One to capture and decode aircraft ADS-B signals, with Python for logging and real-time visualization.

## Overview
This project uses HackRF One to intercept ADS-B signals from aircraft, decoding them with Python to log flight data (e.g., callsign, altitude) and plot positions on an interactive map. It explores signal processing and hardware integration, turning radio waves into visual insights.

## Status
- **Planned (March 2025):**
  - Configure HackRF One on macOS.
  - Capture and decode ADS-B signals.
  - Build Python visualization tool.
- **Current Progress:**
  - [ ] Initialized project structure on GitHub.
- **Goals:**
  - Track local aircraft in real-time.
  - Create a live map display.

## Setup Instructions
### Prerequisites
- macOS system.
- HackRF One ([greatscottgadgets.com](https://greatscottgadgets.com/hackrf/)).
- Python 3.x, libraries: `pyhackrf`, `matplotlib`, `folium`.

### Steps
1. **Set Up HackRF One:**
   - Install HackRF tools (`brew install hackrf`).
   - Test with `hackrf_info`.
2. **Capture Signals:**
   - Use `dump1090` or `pyhackrf` to receive ADS-B at 1090 MHz.
3. **Process Data:**
   - Python script to decode signals and extract flight info.
4. **Visualize:**
   - Log data to `logs/` and plot on a Folium map, displayed via `map.html`.

## Tools & Skills
- **Tools:** HackRF One, Python, dump1090, Folium.
- **Skills:** SDR, signal processing, hardware integration, data visualization.


## Future Enhancements
- Add real-time web dashboard.
- Filter aircraft by region or altitude.
