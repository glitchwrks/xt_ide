XT-IDE rev 3 Bill of Materials
------------------------------

Below is the Bill of Materials for the XT-IDE rev 3 board:

```
Ref(s)      Value                               Mouser P/N
-------------------------------------------------------------------------------
U1, U4      74LS245                             595-SN74LS245N
U2, U3      74F573                              595-SN74F573N
U6, U9      74LS688                             595-SN74LS688N
U5          74LS04                              595-SN74LS04N
U7          74LS138                             595-SN74LS138NE4
U8          74LS32                              595-SN74LS32N
U10         AT28C64B                            556-AT28C64B15PU
SW1, SW2    CTS 208-8                           774-2088
RP1, RP2    10K x 9 SIP resistors               266-10K-RC
R2, R7      10K 1/4 Watt 5%                     603-MFR-25FBF52-10K
R1, R4      470R 1/4 Watt 5%                    660-MF1/4LCT52R471J
D1          HP HLMP-3507                        630-HLMP-3507
J1, J5      2x1 header                          855-M20-9771846 (See Note 1)
J4          5x2 header                          855-M20-9771846 (See Note 1)
J2, J3      3x1 header                          855-M20-9771846 (See Note 1)
C1-C10      0.1 uF 50V axial capacitors         594-A104M15X7RF5TAA
C11         100 uF 6.3V capacitors              647-UMA0J101MDD
SOCKET      28 pin socket for EEPROM            575-199628 
BRACKET     Keystone 9202 ISA bracket           534-9202
SCREWS      4-40 x 1/4" machine screw           534-9301
SHUNTS      0.1" jumper shunts, 2x required     571-3828118 (See note 2)
```

Note 1: Order an 18 (or greater) breakaway header, break into the required lengths.

Note 2: additional jumper shunts are required for IDE Pin 20 power and IRQ selection. Interrupt features are not currently used so no IRQ shunt has been provided in parts kits.

Parts Kits
----------

Parts kits are available from [The Glitch Works](http://www.glitchwrks.com/xt-ide) for $20 USD + shipping. Some substitutions will be made for the above list. The kit is a complete parts kit and includes everything you need to populate an XT-IDE rev 3 board -- you supply the solder and tools. Do note that the parts kit does not include a PC board.

Substitutions
-------------

All 7400 series logic ICs can be substituted for LS, ALS, ACT, or HCT equivalents.

RP1, RP2, R2, and R7 are pull-up/pull-down resistors, their values are noncritical. Anything from 2.2K - 47K should be fine.
R1, R4 tolerance is not critical, but using a substantially different value will alter LED brightness. Do not use less than 220R.
C1 - C10 are power supply bypass, 0.01 - 0.1 uF axial or radial ceramic capacitors are fine.
C11 is for power supply decoupling, any value from 47 uF up is fine, aluminum electrolytic or tantalum.

SW1, SW2 are just 8 position DIP switches, use whatever is cheap/convenient.
D1 is just an indicator, use whatever you'd like
