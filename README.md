# starbie-pcb
A cute little desk buddy, to interact and helpful
Your buddy will play with you, and make you happy

# Starbie

A tiny motion-controlled desk pet on a star-shaped PCB. A little creature wanders around a 128x64 OLED, and you play with it by pressing two key switches, tilting the board and shaking it. A temperature and humidity sensor shows the room's conditions on a stats screen.

Starbie PCB, routed

# What it is

Starbie is my version of the Half Life starter project. The board holds a XIAO ESP32-C3 that runs the pet program, an OLED that shows it, an MPU6050 that senses tilt and shake, a DHT11 that measures temperature and humidity, and two Cherry MX-style key switches for input. The firmware is the single-file Arduino sketch from the Starbie guide (by SharKingStudios), and I changed two pin numbers for my wiring.

# Why I made it

I wanted a small gadget that reacts to you and to the room around it, and I wanted to learn how to take a circuit from a schematic to a finished board. I made the board a star so it looks like a little pet toy rather than a bare circuit, and I covered it in silkscreen line art (koi fish, flowers, palm trees and fireworks) so the back looks as good as the front.

## Bill of Materials (BOM)

| Part | Quantity | Supplier | Unit Cost (USD) | Total Cost (USD) |
|---|---:|---|---:|---:|
| Custom Starbie PCB | 5 | JLCPCB | $1.87 | $9.35 |
| Seeed XIAO ESP32-C3 | 1 | Seeed Studio | $15.86 | $15.86 |
| SSD1306 0.96-inch OLED Display | 1 | Robocraze | $3.09 | $3.09 |
| MX-Compatible Key Switches | 2 | SUNROM | $0.13 | $0.26 |
| DHT11 Temperature and Humidity Module | 1 | ROBODUINO | $1.59 | $1.59 |
| GY-521 MPU6050 Motion Sensor Module | 1 | Robocraze | $2.82 | $2.82 |
| **Total** | | | | **$32.97** |

*Prices are estimates in USD and may vary by supplier. Shipping is not included in the total.*


<img width="1920" height="1080" alt="Screenshot 2026-10-09 190814" src="https://github.com/user-attachments/assets/e311798e-5536-4281-b3bc-759cf8fed659" />
<img width="753" height="656" alt="ss" src="https://github.com/user-attachments/assets/b0936e41-d814-4a69-a63e-8f6824c33dc3" />
<img width="1920" height="1037" alt="Screenshot 2026-10-11 081902" src="https://github.com/user-attachments/assets/bc064d85-6a38-4c5f-b2d4-1717ff7ddd48" />
<img width="1920" height="1030" alt="Screenshot 2026-10-10 104825" src="https://github.com/user-attachments/assets/6e529730-34e6-4ecc-a74f-538a635e717d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-09 190932" src="https://github.com/user-attachments/assets/6b547551-bba1-4dc8-8e18-00d7881c582e" />
<img width="1920" height="1080" alt="Screenshot 2026-10-09 190905" src="https://github.com/user-attachments/assets/5402b569-cd77-481b-9506-eb7ebe5b3fc7" />
<img width="1920" height="1080" alt="Screenshot 2026-10-09 190814" src="https://github.com/user-attachments/assets/1649c0f6-d421-4444-b09e-9fac1a60cb43" />
<img width="1040" height="946" alt="image" src="https://github.com/user-attachments/assets/46315b5c-b689-4f70-b5ec-2e94a959e649" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2ee69847-b79a-41ff-b6b1-e58de56313c4" />
<img width="1076" height="761" alt="image" src="https://github.com/user-attachments/assets/8bd60619-9a78-4554-834c-3fd75c217a07" />
<img width="971" height="801" alt="image" src="https://github.com/user-attachments/assets/30c1dd4c-dfae-4dd0-be7d-ccdb0d69560e" />
