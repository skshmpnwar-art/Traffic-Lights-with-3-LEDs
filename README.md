# Traffic-Lights-with-3-LEDs
Hardware Projects (Arduino)

An introductory Arduino project that simulates a standard traffic light system using Red, Yellow, and Green LEDs. The project sequences the LEDs to mimic real-world traffic signals using timing delays.

## 📸 Project Images

*(Replace the paths below with the actual location of your images in your repository)*

**Completed Project:**
![Traffic Light Project Image](docs/project_image.jpg)

**Circuit Diagram:**
![Traffic Light Circuit Diagram](docs/circuit_diagram.png)

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

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
