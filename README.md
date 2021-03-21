# ESPython DUCO Miner
Hey you, awesome Duino-Coin user!
Are you tired of AVR miners not working? Do you want to mine at night without leaving your PC turned on? Would you like to try mining with ESP devices while keeping the MicroPython firmware in it?

We have the solution: ESPython Miner
A standalone miner for ESP8266/ESP32 devices running MicroPython firmware, it's almost entirely based on the official PC_Miner's code, but adapted to run on this devices without needing to be connected to a computer while mining.

You could copy and paste the code line by line into the Micropython's REPL, but it's obviously better to upload the code to the board, to do that, you can use Thonny Python IDE: Download the ESPythonMiner.py, open it with Thonny, edit the settings, connect your board and upload the code, you'll see the device starting to mine DUCO.

Technical note: Python is obviously much slower than compiled C++ code, that's why this miner uses AVR difficulty instead of ESP32 diff, but this can be changed without problem.

Hope you enjoy it! 👍
