------------PLANT MONITORING SYSTEM--------------

A smart plant monitoring system using the esp32-WROOM-C3 module, and custom designed PCB.

UNIQUENESS OF THE PROJECT
  -Unlike most DIY projects which use the development board, this uses the raw esp32  microcontroller with a custom PCB.

  ------KEY FEATURES------
    - ESP32-WROOM-C3 module with wifi and bluetooth connectivity.
    - Fully custom PCB designed from scratch.
    - Soil moisture sensor, temperature and humidity sensor, and light intensity sensor integrated into the PCB.
    - Uses capacitors for entering the bootloader mode, instead of using manual buttons.
    - micro-USB for programming the microcontroller, with a USB-UART master bridge.
    - Integrated voltage regulator for the optimal 3.3V supply for the esp32.
    - Barrel-jack for external power, with Schottky diode to prevent backfeeding when multiple power sources are present.
    - Optioinal cloud connectivity.
    - Designed for low-cost scalable deployment.

-----------HARDWARE OVERVIEW-------------
    - ESP32-WROOM-C3 bare module
    - AMS1117 3.3V regulator (or similar LDO)
    - USB-to-Serial (CH340 / CP2102) for flashing/debug
    - Soil Moisture Sensor
    - DHT11 or DHT22 Sensor
    - Relay Module (optically isolated)
    - Decoupling capacitors, pull-up resistors.
-----------PCB DESIGN--------------
    - Designed in KiCAD
    - custom Copper route, antenna clearance.
    - Proper boot configuration circuitry.
    - USB and power input protection.

    <img width="1582" height="1036" alt="Screenshot 2025-07-19 at 9 59 57 PM" src="https://github.com/user-attachments/assets/20fba216-77c1-4ec9-a74e-19b4c783a5b9" />
    <img width="1582" height="966" alt="Screenshot 2025-07-19 at 9 59 38 PM" src="https://github.com/user-attachments/assets/b7abec22-c398-4af1-8a90-3bc49990c671" />

