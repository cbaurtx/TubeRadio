#TubeRadio
## Disclaimer
It is entirely your responsibility to comply with all 
applicable laws when possesing or operating this radio.
It is entirely your responsibility to make sure the all circuits, including the powersupply are operated safely.
## License
TubeRadio is covered by CERN-OHL-W (Weakly reciprocal) 
Refer to doc/LICENSE.md for the license text
## Notes
### Output Transformer
There is a DC bias flowing through the output transformer. To avoid magnetic saturation of the iron core the core needs a small paper/plastic gap (~0.1–0.3 mm) between E and I laminations. Do not use a power
transformer or an audio transformer for a push pull amplifier.
### Input Tank and Tickler Coil
The target frequency range of this radio is from 1.50MHz to 4.25MHz. With a capacity of 70pF to 570pF we can calculate the inductance of the coil of the input tank.

**f₀ = 1 / (2π × √(L × C))**

**f₀** is the resonance frequency in hertz (Hz)

**L** is the inductance in henrys (H)

**C** is the capacitance in farads (F)

To get the calculted inductance of 20µH the input tank 
coil we need this air coil:


|Entity |Value|Unit|
|-------|-----|----|
|Turns  |25   |#   |
|Layers |2    |#   |
|Inner ø|13   |mm  |
|Wire ø |0.9  |mm  |


The antenna and the tickler coil both have 8 turns.
The antenna coil is wound on to of the input tank coil and the tickler coil is side by side pf the other coils at a distance of 10mm.




