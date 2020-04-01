# Protocol for the Production of WSN Flu Virus

Make WSN virus, both wild-type (WT) and double barcoded (BC). The double barcoded virus has a synonymous mutation near the 5' end and 3' end of each vRNA segment. Made by Alistair Russel.

Submitted by David Bascik.

SAFETY CONSIDERATIONS:

Importantly, flu virus is a BL2 level agent. This means *all* disposables must be disinfected by sterilization with at least a 1:200 dilution of Wescodyne (under the sink in TC room). All plates should be sterilized by soaking in Wescodyne solution for a minimum of 10 minutes, then aspirated, taped, and disposed of in the virus waste bin under the hood. All disposables should be doubly-contained, either in the small red autoclave bags (pipettes), or in empty P1000 tip boxes (small disposables). These should be taped closed and disposed of in the virus waste bin at the end of the experiment. 

## Reagents Needed

- 6-well TC-treated dishes
- PBS
- D10
- WT influenza plasmids, OR
  - [31--PB1](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/31_pHW182_PB1.gb)
  - [30--PB2](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/30_pHW181_PB2.gb)
  - [32--PA](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/32_pHW183_PA.gb)
  - [33--HA](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/33_pHW184_HA.gb)
  - [34--NP](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/34_pHW185_NP.gb)
  - [35--NA](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/35_pHW186_NA.gb)
  - [36--M](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/36_pHW187_M.gb)
  - [37--NS](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/37_pHW188_NS.gb)
- double barcoded influenza plasmids
  - [1642--PB1_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1642_pHW182_PB1_double_syn.gb)
  - [1641--PB2_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1641_pHW181_PB2_double_syn.gb)
  - [1643--PA_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1643_pHW183_PA_double_syn.gb)
  - [1644--HA_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1644_pHW184_HA_double_syn.gb)
  - [1645--NP_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1645_pHW185_NP_double_syn.gb)
  - [1646--NA_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1646_pHW186_NA_double_syn.gb)
  - [1647--M_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1647_pHW187_M_double_syn.gb)
  - [1648--NS_doublesyn](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/1648_pHW188_NS_double_syn.gb)
- positive control plasmid [208--PB1flank_GFP](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/208_pHH_PB1flank_eGFP.gb)
- 1.7 mL microcentrifuge tubes
- DMEM
- Bio-T transfection reagent
- WGM (WSN Growth Medium)

## Protocol

### Day 1

1. Seed 293Ts and MDCKs in a 6-well dish at a density of:
  - MDCKs: 0.5e5 cells/well
  - 293Ts: 4e5 cells/well

### Day 2
2. Ensure the cells are 40-60% confluent.
3. Add 250 ng each plasmid.
  - for a negative control, leave out one plasmid
  - for a positive control, add 250 ng of the positive control plasmid (#208)
  - make an 8X master mix 1 (MM1) of common segments: PA, NP, NA, M
  - make a 4X master mix 2 (MM2) of potential unique segments: PB2, PB1, NS, HA
    -leave out any segments that are unique of this master mix
4. Distribute 10 uL MM1 (WT) or 10.5 uL MM1 (BC) to appropriate sample tubes (1.7 mL microcentrifuge tubes)
5. Distribute 10 uL MM2 (WT) or 11.2 uL MM2 (BC) to appropriate sample tubes. 
6. Add 250 ng of any unique segment to appropriate sample tubes
7. Make room temperature master mix of DMEM and Bio-T:

Reagent | vol per 1 sample (ul)
--- | ---
DMEM | 100
Bio-T | 3

8. Add 103 uL DMEM/Bio-T master mix to all sample tubes
9. Mix extremely well
10. Incubate at room temp 15 minutes
11. Gently, dropwise, add the DNA/DMEM/Bio-T transfection mix to appropriate wells
12. Gently mix by rocking

### Day 3

13. Ensure cells are ~50ish% confluent and mostly attached
14. 24 hours post infection, aspirate media
15. Gently add 2 mL WGM

### Day 4

16. 48 hours post infection, collect supernatant
17. Centrifuge at 2000 RCF for 5 minutes
18. Aliquot to cryo tubes. Store at -80˚C
