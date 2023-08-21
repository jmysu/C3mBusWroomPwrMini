### Wokwi simulation w/ C3mBusMini Custom Board 

<img src="C3mBusMiniNeo3Btn0819.png" width=65%> <br>
<img src="C3mBusMiniNeo3Btn0819.gif" width=30%> <img src="C3mBusBz0820.gif" width=30%> <br>
<br>

---

### Wokwi custom board (mini how-to) 

  - Go WokWi [ESP32C3 Starter page](https://wokwi.com/projects/new/esp32-c3) <br>
  - In the code editor, hit "F1", "Load custom board file...", select the board folder! <br>
  - Update Diagram.json <br>
    Change "parts", "type":"xxxxxxxxx" to "type":"wokwi-custom-board" <br>
    Change "connections", "esp:TX" to "esp:TX21"; "esp:RX" to "esp:RX20"; _(board drawing will change to C3mBus!)_
        <img src="C3Starter_Diagram.json.png"> <br>
  - Update Sketch.ino <br>
        <img src="C3Starter_Sketch.ino.png"> <br>
  - Run the simulator <br>

  
---

### Reference

[Wokwi custom board](https://github.com/wokwi/wokwi-boards) How to load custom board on Wokwi project? <br>
[Wokwi Simulation](https://wokwi.com/) Simulate IoT Projects in Your Browser.<br>

