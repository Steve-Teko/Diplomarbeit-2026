# Diplomarbeit-2026
Offizielle Repository fuer die Diplomarbeit von Steve


**Idee:**
Die Idee ist es Leiterplatten zu designen, die in einem neuen oder bestehenden SmartHome mit einfachen Schritten integrierbar sind.
Es sollen einfache aber Funktionsreiche Leiterplatten die z.B. im Fall des Aktor Prints, per I2C an bereits vorhandene Steuerungen verwendet werden koennen.


**Meine Qualifikationen:**
Gelernt habe ich Automatiker und interessiere mich seit meiner Kindheit fuer viele Technik relevante Themen. Schulisch war ich schon immer einer dem die Themen Kunst und Sprachen weniger interessierten im vergleich zu Mathe, Physik und Handarbeit.
Mit 23 hatte ich eine Entscheidung getroffen, mich Schulisch weiterzubilden. Dies ist bis jetzt immer noch eine Entscheidung die ich nicht bereue. Der Weg bis zu dieser Arbeit war steinig und hart.
Leiterplatten hatte ich einmal in der Lehre mit meinem damaligen Lehrlingsbetreuer gezeichnet, dies aber danach nie mehr ausgefuehrt. Damals hatten wir Eagle als Programm.

**Die Umsetzung:**
Zu diesem Repo existiert noch meine Arbeit die ich Paralell dazu Schreibe. Die Idee des Repo ist es die notwendigen Daten: KiCad, Gerber Files, Gehause oder Programmzeilen fuer spaetere vorhaben zu Speichern.
Die Arbeit werde ich nicht auf das Repo hochladen.

**Haftungsausschluss:**
Ich bin weder fuer die korrekte Anwendung noch meine Fehler Verantwortlich, saemtliche Schaeden die durch alle Dateien auf diesem Repo verursacht wurden, sind alleinig dem Anwender zuzuschreiben.
Die Leiterplatten sind von keinem Pruefunternehmen abgenommen oder auf ihre Sicherheit geprueft worden. Bei Verwendung sind alle Regeln der Technik zu beachten.


#################################################################################################

Official repository for Steve's diploma thesis.

**Idea**
The concept is to design printed circuit boards (PCBs) that can be easily integrated into a new or existing smart home system.
The goal is to create simple yet feature-rich PCBs—such as the actuator board—that can connect to existing control systems via I2C.

**My Qualifications**
I am a trained automation technician (Automatiker) and have been interested in various tech-related topics since childhood. At school, I was always far less interested in art and languages compared to math, physics, and practical crafts.
At age 23, I decided to further my education—a choice I still do not regret. The path leading up to this project has been tough and challenging.
I had designed PCBs once during my apprenticeship alongside my mentor using EAGLE, but I never worked with PCB design again after that.

**Implementation**
In addition to this repository, I am writing my written thesis in parallel. The purpose of this repo is to store the necessary project files—such as KiCad files, Gerber files, enclosure models, or code lines—for future reference.
I will not be uploading the written thesis itself to this repository.

**Disclaimer**
I am responsible neither for the correct application of these files nor for any errors within them. Any damages caused by files in this repository are solely the responsibility of the user.
The PCBs have not been certified or safety-tested by any official inspection body. When using them, all applicable engineering standards and safety codes must be strictly followed.



**What to expect:**
You will be able to order a the Following PCB from your favorite PCB Manufacturer, the Files and a basic Enclosure designed in FreeCAD is included in the Folders

**Hauptprint aka the Brain**
It's purpose is being able to be integrated in to your existing SmartHome while offering a wide range off preconfigured In/Output.
The ESP32 C6 Wroom1 supports Thread/Zigbee, Wi-Fi 6 (2.4gHz only!), Bluetooth 5.0, UART, I2C and I2S.

![alt text](https://github.com/Steve-Teko/Diplomarbeit-2026/blob/main/HauptprintV1/HauptprintV1/HauptprintV1.png)


**The RelaisExpanderPrint aka the Switchmaster**
The RelaisExpanderPrint was designed with compatibility and versatility in mind. The Idea was to create a 16x Relays Switching device with Potential-free contacts in mind, as you would find on a PLC or in an Switching Cabinet.
Its size is as compact as i was able to design it with an Power-supply input that support different Voltage Levels depending on your needs.
The TracoPower Component (PS1) is interchangeable in its product line so you can choose Supply Voltages ranging from 9V,12V,24V or up to 75V DC. 


![alt text](https://github.com/Steve-Teko/Diplomarbeit-2026/blob/main/RelaisExpanderPrintV1.0/RelaisExpanderPrintV1.0/RelaisExpanderPrintV1.0.png)
