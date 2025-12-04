# micropad!
This is a 12-key 'macro'pad with an OLED display and LEDs underneath the keys!
I plan on using this as a numberpad, with extra keys (calculator, gamebar).

# Schematic and PCB!
<img width="2533" height="1178" alt="image" src="https://github.com/user-attachments/assets/950e12c6-517e-4032-ab0f-3dd210036a30" />
<img width="1070" height="1029" alt="image" src="https://github.com/user-attachments/assets/541a8f3d-52c6-432d-89e6-ac976149b3f5" /> <img width="1069" height="1024" alt="image" src="https://github.com/user-attachments/assets/1a8933c4-3ed0-411e-b543-be0d348ba8a4" />
These were made in KiCad. There are two layers in this PCB. The top serves as the signal plane while the bottom serves as the ground plane.

# CAD
Here is the assembled piece within AutoDesk Fusion 360! I was unable to find 3D models for the LEDs. The microcontroller also wouldn't export to Fusion360. Below I attached the KiCad PCB model and the Fusion360 model.
<img width="1253" height="1218" alt="image" src="https://github.com/user-attachments/assets/435735b4-2074-42d6-af88-6a8b4859e3c1" />
<img width="1661" height="1002" alt="image" src="https://github.com/user-attachments/assets/4498be2f-a7d5-4509-956a-93a024b45255" />
I separated the model into two pieces to print.
<img width="1141" height="695" alt="image" src="https://github.com/user-attachments/assets/227e29d1-fe01-4e7c-87d7-3a051672ee46" />
<img width="1473" height="847" alt="image" src="https://github.com/user-attachments/assets/4a772817-f157-44ce-8aea-68ae69fd2188" />

# Parts Used
| Quantity | Item                      |
|---------|----------------------------|
| 1       | XIAO RP2040                |
| 1       | 3D printed case: base      |
| 1       | 3D printed case: cap       |
| 9       | SK6812MINI LEDs            |
| 12      | Cherry MX Switches         |
| 12      | DSA Keycaps                |
| 1       | 0.91" 128x32 OLED Display  |
