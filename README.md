# Traffic-Lights-with-3-LEDs
Hardware Projects (Arduino)

An introductory Arduino project that simulates a standard traffic light system using Red, Yellow, and Green LEDs. The project sequences the LEDs to mimic real-world traffic signals using timing delays.

## 📸 Project Images

*(Replace the paths below with the actual location of your images in your repository)*

**Completed Project:**
<img width="2268" height="4032" alt="IMG_6397" src="https://github.com/user-attachments/assets/90cdccad-f92b-445f-948c-9e28b32d50d5" />
<img width="2268" height="4032" alt="IMG_6398" src="https://github.com/user-attachments/assets/a9b10716-081e-4521-905f-564a31c6a816" />
<img width="2268" height="4032" alt="IMG_6395" src="https://github.com/user-attachments/assets/139fe827-ea7c-4c57-96fe-e4ed00065aec" />




**Circuit Diagram:**
<img width="915" height="739" alt="image" src="https://github.com/user-attachments/assets/8a6607fc-c0a4-4c57-bd55-ab184f664830" />


## 🛠️ Components Required

* 1x Arduino Uno (or compatible board)
* 1x Breadboard
* 1x Red LED
* 1x Yellow LED
* 1x Green LED
* 3x 220Ω Resistors (one for each LED)
* Jumper Wires
* USB Cable

## 🔌 Wiring Instructions

Connect the components on your breadboard according to the following pin configuration:

1. **Ground:** Connect the long ground rail of the breadboard to one of the **GND** pins on the Arduino.
2. **Red LED:** * Connect the **Anode** (long leg) to Arduino **Digital Pin 12**.
   * Connect the **Cathode** (short leg) to the ground rail through a 220Ω resistor.
3. **Yellow LED:** * Connect the **Anode** (long leg) to Arduino **Digital Pin 11**.
   * Connect the **Cathode** (short leg) to the ground rail through a 220Ω resistor.
4. **Green LED:** * Connect the **Anode** (long leg) to Arduino **Digital Pin 10**.
   * Connect the **Cathode** (short leg) to the ground rail through a 220Ω resistor.


### Code Logic Breakdown:
* **Green Light:** Stays on for 5 seconds.
* **Yellow Light:** Stays on for 2 seconds to signal a transition.
* **Red Light:** Stays on for 5 seconds.

## 🚀 How to Run

1. Make sure your repository is structured with the code folder named exactly `Traffic_Lights_3_LEDs` containing the `Traffic_Lights_3_LEDs.ino` file.
2. Open the `Traffic_Lights_3_LEDs.ino` file using the Arduino IDE.
3. Connect your Arduino board to your computer.
4. Select your correct **Board** and **Port** under the **Tools** menu.
5. Click **Upload** to flash the code to your Arduino.


