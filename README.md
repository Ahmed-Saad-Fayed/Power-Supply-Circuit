-Power-Supply-Circuit
This project demonstrates a dual-output regulated power supply using two voltage regulators: 7809 (9V output) and 7805 (5V output).

⚙️ Circuit Description
TR1 (Transformer): Steps down the AC voltage from the mains to a suitable level for the rectifier.

BR1 (Bridge Rectifier): Converts AC to pulsating DC.

C1 (Filter Capacitor): Smooths the pulsating DC from the bridge rectifier.

U1 - 7809 Regulator: Regulates the voltage to a stable 9V.

U2 - 7805 Regulator: Regulates the voltage to a stable 5V.

C3, C4 (Decoupling Capacitors): Help to filter out noise and stabilize the output.

D1, D2 (LEDs with R1, R2): Indicate the presence of output voltages (visual status indicators).

Output Load: Connected to test the 5V and 9V outputs.

💡 Features
Dual voltage output: +9V and +5V.

LEDs for output indication.

Noise filtering and voltage smoothing.

Simple and effective linear regulated power supply.

🧪 Tools Used
Proteus: For circuit simulation and testing.

Electronic Components: Transformer, bridge rectifier, voltage regulators, capacitors, resistors, LEDs.
