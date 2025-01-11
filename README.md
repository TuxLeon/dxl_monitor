Usage

Connect OpenCM9.04 to XL320 servos

baud 1000000 (Set Bautrate to 1.000.000) 

scan (List all detected servos)


Example commands:

help (Get help info)

wrb2 2 1 (enable Torque on ID=2. Needed before all movement)

rdw2 2 32 (Read a Word (w) from ID=2 in velocity register (32) 

wrw2 2 32 1023 (Set Velicity to 1023 "full speed ahead")

wrw2 2 32 1023 (Set Velicity to 1023 "full speed ahead")
