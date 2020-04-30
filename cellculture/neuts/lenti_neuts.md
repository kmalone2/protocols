# Protocol for Pseudotyped Lentiviruses

Submitted by Kate Crawford.

This protocol was developed for SARS-CoV-2 pseudotyped lentivirus neutralization assays. It is therefore optimized for those assays, and will need to be tweaked for different VEPs.

Written as described in [Crawford et al 2020](https://www.biorxiv.org/content/10.1101/2020.04.20.051219v1.full.pdf). 

## Materials Needed

- cells expressing the receptor of interest
- pseudotyped lentivirus
- poly-L lysine coated 96 well plates
- DMEM
- D10
- polybrene
- sample to test for virus neutralization
- Bright-Glo luciferase system (Promega #E2610)
- Costar black bottom 96 well plates (Fisher #07-200-590)

## Protocol

### Day 1
1. Seed a poly-L lysine coated 96 well plate with 1.25e4 293T-ACE2 cells (BEI NR-52511) per well in 50 uL DMEM (2.5e5 cells/mL)

### Day 2
2. 8-12 hours post seed, prepare for infection
3. in a separate 96 well setup plate, serially dilute serum samples leaving 60 uL diluted serum in each well
4. add 60 uL D10 to wells corresponding to virus and virus + cell only controls
5. add 120 uL to media only and cell only control wells
6. Dilute virus to 2-4e6 RLUs per mL. Add 60 mL of this diluted virus to all wells containing serum and to the virus only and virus+cell control wells
7. Incubate plate at 37C for 1h
8. Carefully add 100 uL of the setup plate (containing sera+virus incubated wells) to corresponding wells of the plate with cells
9. Add polybrene to a concentration of 5 ug/mL per well
  - add 3uL polybrene diluted to 250 ug/mL to the final infection volume of 150 uL
10. Incubate at 37C for 48-60h before reading luminescence or fluorescence
11. Plot the data using [neutcurve](https://jbloomlab.github.io/neutcurve/index.html)

### Reading via Luciferase

1. thaw luciferase reagent at room temperature 
2. Prepare cells by removing 100 uL media from each well (leaves about 30 uL in each well)
3. Add 30 uL luciferase reagent and mix well
4. Transfer all 60 uL to a black bottom plate
4. Incubate at room temperature *in the dark* for 2 minutes 
5. Measure luminescence on a plate reader 
  - no attenuation and luminescence integration time of 1 second 



