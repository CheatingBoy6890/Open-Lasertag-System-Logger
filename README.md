# Open-Lasertag-System

![_DSC8902](https://github.com/user-attachments/assets/2fc5b138-46ba-4c61-b85c-79018dc33adf)

---

<img src="https://github.com/user-attachments/assets/9b382106-baaf-4b78-8249-ecbceb030ddd" width="60">
https://commons.wikimedia.org/w/index.php?curid=1668938

Warning: This project uses lasers. Be sure to **always** do your own testing by meassuring voltage and current and by looking in datasheets. I am **not** responsible for any injuries you encounter from using this project. Also make sure to wear proper eye-protection.

---

<h2>What is Open-Lasertag-System?</h2>
Open-Lasertag-System is our approach to a build Lasertag that can be played anywhere without the need of setting up repeaters or servers, whilst beeing pretty easy to build and extend to fit your needs. It works decentral using a WIFI mesh,so the range and fun extends the more players you have!

Currently the project consists of four parts:

1.  The Taggers are fully functional with features such as different firemodes and score synchronization
2.  The vests. The first prototype is built but not yet tested with the taggers.
3.  Targets : For those who don't want to shoot at each other can just shoot at these. The plan also ist to intergrate the further into the system for modes like capture the Flag
4.  Logger: Counts wich target have been hit by whom

---

<h2>What is this repository?</h2>

This is the repository for the logger that can be used toghether with the targets to make a parcour with a timer that decreases the more targets are hit by the player.
**What you'll need:**

- An ESP8266 or ESP32
- An TFT Display
- 4 Buttons (in 4 different colors)
- 4 LEDs (in 4 different colors)
