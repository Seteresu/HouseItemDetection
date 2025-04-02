# House Item Detection

House Item Detection is a project that utilizes TensorFlow Lite from Edge Impulse to detect three types of objects: **Keys, Remote, and Glasses**. The system is designed to run on an **ESP32-CAM**, making it a portable and efficient solution for object recognition.

## Requirements

### Hardware Setup
To set up the hardware, you will need:
- **ESP32-CAM**
- **Breadboard**
- **FTDI Serial to USB Connector**
- **Mini-B USB Cable**
- **Five mid-length female-to-female jumper wires**
- **Battery pack (for portable use)**

These components can be purchased from online retailers such as **Amazon** and **Walmart**.

### Software Setup
- **Arduino IDE** (Installed on your computer)
- **ESPRESSIF ESP32-CAM Library** (Installed in Arduino IDE)
- **Edge Impulse** (Accessible via a web browser for model training and deployment)

## Installation Steps

### 1. Install the Edge Impulse Model
After training your model on Edge Impulse, download the generated `.zip` file to your computer.

### 2. Add the Library to Arduino IDE
1. Open **Arduino IDE**.
2. Click on **Sketch** (located in the top menu).
3. Hover over **Include Library**.
4. Click on **Add .ZIP Library**.
5. Select the downloaded `.zip` file and upload its contents.

### 3. Upload the Code to ESP32-CAM
1. Download the `.ino` file from **GitHub**.
2. Connect your **ESP32-CAM** to your computer using the **FTDI Serial to USB Connector**.
3. Ensure that your **ESP32-CAM** is in **Download Mode**.
4. Click the **Upload** button in Arduino IDE (**turquoise circle with a right arrow**, located at the top-left next to the checkmark and debug symbols).
5. Wait for the upload process to complete.
   - If errors occur, check both **hardware and software configurations**.
   - Refer to **ESP32-CAM layout documentation** for troubleshooting.
6. Once successful, the output screen will confirm the upload.

### 4. Powering the ESP32-CAM
1. Remove the **USB cable** and switch to the chosen **power source** (battery pack or other alternatives).
2. The system will begin detecting objects and outputting results.

## Training Your Own AI Model
To create a custom AI object-identification model, refer to the following tutorial:
[Object Recognition using ESP32-CAM and Edge Impulse](https://circuitdigest.com/microcontroller-projects/object-recognition-using-esp32-cam-and-edge-impulse)

## Acknowledgments
Special thanks to:
- **Rithik Krisna**
- **Nakia Crumbo**
- **Dr. Swarna Sethu**


