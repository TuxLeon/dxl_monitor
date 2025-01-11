# Markdown usage on github
[Markdown help](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet)

# Usage

* Connect OpenCM9.04 to XL320 servos
* Flash Sketch
* set "Carriage Return" in Monitor App
* baud 1000000 (Set Bautrate to 1.000.000) 
* scan (List all detected servos)
* help (Get help info)

# Commands
| Command       | Meaning            |
| ------------- |:------------------:|
| rdb2          | read byte          |
| rdw2          | read word (2 Byte) |
| wrb2          | write byte         |
| wrw2          | write word (2 Byte)|

# XL320 Datasheet
[XL320](https://emanual.robotis.com/docs/en/dxl/x/xl320/)

# Example commands

help (Get help info)

* wrb2 2 1 (enable Torque on ID=2. Needed before all movement)
* rdw2 2 32 (Read a Word (w) from ID=2 in velocity register (32) 
* wrw2 2 32 1023 (Set Velicity to 1023 "full speed ahead")
* wrw2 2 32 1023 (Set Velicity to 1023 "full speed ahead")
