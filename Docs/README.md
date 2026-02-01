# IntelliLoft-IoT-Based-Smart-Home-Network Simulation

This project is a **Smart Home IoT simulation** built in **Cisco Packet Tracer**. It demonstrates the integration of IoT devices such as smart lights, thermostats, sensors, and gateways in a home automation setup.

---

## Features

- Wireless connection of IoT devices to a central home gateway.
- Automation logic for:
  - Motion-triggered lighting
  - Temperature-based thermostat control
  - Smart door locks
- DHCP and IP management for IoT devices.
- Modular device configuration for easy expansion.

---


## Getting Started

1. Install **Cisco Packet Tracer** (v8.x recommended).
2. Open the simulation file located in `simulations/smart_home_v1.pkt`.
3. Power on all IoT devices in the **Physical tab**.
4. Connect devices to the **wireless router** using SSID `HomeWiFi` (WPA2 or open for testing).
5. Check **Status** in Config → Wireless to ensure connection.
6. Test automation:
   - Motion sensor triggers lights.
   - Thermostat reacts to temperature changes.
   - Ping devices from router to verify connectivity.

---

## Modules

- **Lights:** Configuration and automation logic for smart lights.
- **Thermostat:** Temperature sensing and automatic control.
- **Sensors:** Motion and temperature sensors with triggers.
- **Gateway:** Router/AP setup for wireless IoT network.

---

## Troubleshooting

- If IoT devices do not connect:
  - Ensure they are **powered on** in the Physical tab.
  - Verify SSID and password match the router.
  - Use **Real-Time mode** instead of Simulation mode for testing.
  - Check router DHCP table for assigned IPs.


