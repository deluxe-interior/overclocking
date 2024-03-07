There are five main voltages that are essential for overclocking DDR5 memory. They are all interrelated. If you change one it can impact the others.
- VDDQ TX Voltage
- IMC VDD Voltage
- System Agent Voltage
- VDD Voltage (VDIMM)
- VDDQ Voltage

**VDDQ TX Voltage (IVR Transmitter VDDQ Voltage)**
- This is the * real * memory controller voltage on the CPU. 
- It is the CPU side that powers the memory. 
- You should start off with a good baseline and park it there as you tune other voltages
    - 1.35 is ideal; if you can go that low
    - 1.40 is good.
    - Can go up to 1.45. Anything above that will likely be unstable (at least on 12900k - 14900k)
- Essentially throttles inbound bandwidth so that you can tune the other voltages
- If it is too high you will struggle with the other voltages.

**IMC VDD**
- This is the memory controller voltage on the motherboard. 
- It interacts with VDDQ TX Voltage.
- You shoudl start off with a good baseline and park it there.
- 1.35 is ideal; if you can go that low
- 1.40 is common for me.
- Can go up to 1.45. Anything above that will likely be unstable (at least on 12900k - 14900k)
- Essentially throttles inbound bandwidth so that you can tune the other voltages
