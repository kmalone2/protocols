# Protocol for ELISA with SARS-CoV-2 Immunogens

This is a protocol from [Stadlbauer et al. 2020](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpmc.100). Suggested to be important by Adam Dingens, so included as a write-up here. 

This is a two stage ELISA. The first stage is ELISA with SARS-CoV-2 receptor binding domain (RBD), for high throughput screening of potentially positive serum samples. The second is ELISA with full-length Spike protein. This second stage is run with a dilution curve of potentially positive serum samples.

Safety Considerations: These samples could have interacted with SARS-CoV-2. Consult with Jesse or Andrea about appropriate PPE and biosafety precautions before handling any samples.

## Materials Needed
- plate washer
- plate reader
- appropriate negative controls (serum pools pre-2020)
- appropriate positive controls 
  - harder to come by
  - convalescent samples from COVID-19 patients
  - human mAb CR3022
- recombinant RBD protein
- Recombinant full-length Spike protein
- 1 x PBS
- serum or plasma samples to test
- PBS-T
  - recipe for 10 L below:
  - 9 L dH2O
  - 5 L 10x PBS
  - 50 mL Tween 20 (Fisher Bioreagents #BP337-500)
- Milk Powder (AmericanBio #AB10109-01000 or equivalent)
- Anti-human IgG (Fab-specific)-horseradish peroxidase (HRP) labeled secondary antibody produced in goat (Sigma-Aldrich #A0293)
- SIGMA*FAST* OPD (Sigma-Aldrich #P9187)
- Water for injection (WFI) for cell culture (Gibco #A1287301)
- 3M HCl
- ELISA plates: flat bottom Immuno nonsterile 96-well plates 4 HBX (Thermo Scientific #3855)
- 50-250 uL multichannels
- reagent resevoirs
- Class II Biological safety cabinet
- 1.5 mL microcentrifuge tubes
- flat bottom cell culture plates

## Protocol for RBD Screening ELISA

### Day 1: Coat ELISA plates and heat inactivate serum
1. Thaw required number of vials of antigen (RBD) to coat the 96-well microtiter ELISA plates at a conc of 2 ug/mL
  - each plate will require approx 5 mL
2. Coat plates by adding 50 uL diluted antigen per well using a multichannel. Ensure protein evenly covers the surface of each well.
3. Incubate at 4C overnight. *Note: the authors say the plates will likely be okay at 4C for up to a week. This should be validated.*
4. Heat inactivate serum samples by incubation at 56C for 1 h.

### Day 2

5. prepare 30 mL blocking solution per plate (PBS-T + 3% w/v milk powder)
6. Wash coated ELISA plates 3x with PBS-T
7. Add 200 uL blocking solution to all wells. Incubate at least 1h, but no longer than 4h at room temperature,
8. Pre-dilute serum samples. In a BSC, set-up 1.5 mL epi tubes to dilute serum samples at 1:5 ratio. Make 50 uL of each serum dilution to use for both ELISAs. 
9. Prepare one dilution plate per antigen coated plate
10. Prepare 30 mL PBS-T + 1% w/v milk powder. Add 180 uL of this solution to each well of the dilution plate.
11. Leaving columns 1 and 12 as blanks, add 20 uL of diluted sample or control to the designated wells (final serum dilution is 1:50)
12. Remove blocking solution from antigen coated plates. Tap dry on a Kimwipe.
13. Using a multichannel, mix the first row of wells in the dilution plate. Then transfer 100 uL to the corresponding wells in the antigen-coated plate. 
14. Repeat for remaining rows, changing tips each time.
15. After transferring all rows, start a timer for 2 h, incubate at room temp. Do not exceed 4h.
16. Wash ELISA plates 3x with PBS-T
17. Dilute secondary antibody 1:3000 in PBS-T + 1% w/v milk powder. Prepare at least 5 mL per plate
18. Add 50 uL secondary antibody solution to all wells of ELISA plate. 
  - Be sure to avoid touching the walls of the wells with the pipette tips, to avoid carry-over and high background signals
19. Incubate at room temperature for no less than 50 min, but no greater than 65 min (start timer with first addition of secondary antibody).
20. After incubation, wash 3x with PBS-T.
21. Prepare SigmaFast OPD solution immediately before use
  - one set of tablets dissolved in 20 mL WFI can be used for 2 ELISA plates
22. Add 100 uL OPD solution to all wells of the plate. Begin timer for 10 min as soon as the OPD solution is added to the first row of the first plate. 
23. After exactly 10 min, stop the reaction by adding 50 uL 3M HCl
24. Read ELISA plates in a plate reader at an absorbance of 490 nm
  - potential positives are those that exhibit a signal above the mean + 3 standard deviations of the negative controls. This has to be experimentally determined, though a proposed starting point if a cutoff of OD490 = 0.15 to 0.2

## Protocol for Spike confirmatory ELISA

### Day 1: Coat ELISA plates
1. Thaw required number of vials of antigen (RBD) to coat the 96-well microtiter ELISA plates at a conc of 2 ug/mL
  - each plate will require approx 5 mL
2. Coat plates by adding 50 uL diluted antigen per well using a multichannel. Ensure protein evenly covers the surface of each well.
3. Incubate at 4C overnight. *Note: the authors say the plates will likely be okay at 4C for up to a week. This should be validated.*

### Day 2

4. prepare 30 mL blocking solution per plate (PBS-T + 3% w/v milk powder)
5. Wash coated ELISA plates 3x with PBS-T
6. Add 200 uL blocking solution to all wells. Incubate at least 1h, but no longer than 4h at room temperature.
7. Retrieve the pre-diluted samples that are potentially positive from the results of the RBD ELISA.
9. Remove the blocking solution and tap the plates dry on a Kimwipe
8. Serially dilute each sample 6x as below:
  - add 120 uL PBS-T + 1% w/v milk powder (at least 20 mL per plate) to all wells
  - add an extra 51 uL of PBS-T + 1% w/v milk powder to **columns 2 and 7** (sample columns)
  - add 9 uL of 1:5 pre-diluted potentially positive serum samples (final dilution 1:100 in this well) to each well of column 2 and column 7 wells A-F (G and H are negative and positive control wells)
  - using multichannel, mix well in column 2. Discard tips. With new tips, transfer 60 uL sample to the next column and mix well. Repeat for columns 3-6, removing and discarding 60 uL of sample after mixing in column 6. 
  - repeat step above for samples starting in column 7. Discard sample after column 11 (as columns 1 and 12 are blanks)
9. Once first plate has been serially diluted, start timer for 2h. Do not exceed 4 h of incubation before the next step.
10. Wash ELISA plates 3x with PBS-T
11. Dilute secondary antibody 1:3000 in PBS-T + 1% w/v milk powder. Prepare at least 5 mL per plate
12. Add 50 uL secondary antibody solution to all wells of ELISA plate. 
  - Be sure to avoid touching the walls of the wells with the pipette tips, to avoid carry-over and high background signals
13. Incubate at room temperature for no less than 50 min, but no greater than 65 min (start timer with first addition of secondary antibody).
14. After incubation, wash 3x with PBS-T.
15. Prepare SigmaFast OPD solution immediately before use
  - one set of tablets dissolved in 20 mL WFI can be used for 2 ELISA plates
16. Add 100 uL OPD solution to all wells of the plate. Begin timer for 10 min as soon as the OPD solution is added to the first row of the first plate. 
17. After exactly 10 min, stop the reaction by adding 50 uL 3M HCl
18. Read ELISA plates in a plate reader at an absorbance of 490 nm
  - true positive samples will have a signal higher than the negative control + 3 standard deviations of negative controls in at least 2 consecutive dilutions
