# Protocol for Klenow Reactions

Submitted by Kate Crawford. 

## Reagents Needed

- library oligos (100uM)
- SerologySeq Primer
- NEB Buffer 2
- molecular biology grade water
- Klenow
- dNTPs (preferably 10 mM TOTAL, 2.5 mM each; or 250 uM dNTP stock)
- PCR tubes
- [Zymo Clean and Concentrate DNA kit](../kits/zymo.md)

## Protocol

1. Prepare Master Mix:
- 10 uL 100uM Library Oligos [this is ~2.7ug/uL, but only ~6e13 oligos/uL] <- when I go to package, I can only package ~1e10 oligos/rxn anyway
- 11 uL 100uM 3’-SerologySeq primer (primer in slight excess)
- 8 uL NEB Buffer 2 (10x)
- ~37.5 uL H2O <- varies based on klenow and dNTP volumes added
- Total: 80uL

2. Prepare 27 U of Klenow (for 1 U per ug DNA). Have 5000 U/mL = 5 U per uL, so add ~5.5 uL Klenow. 
3. Prepare at least 33 uM dNTPs. Have 10 mM. Would need 0.264 uL 10 mM dNTPs. 
  - Note: However, did the math and 10 uL of 100 uM oligos with (a guess of) 80 bp of overhang, means I have ~4.8e16 bp to add, so need 1 mM of dNTPs to add that many bases. Assuming an even split of bases, I could add 250 uM of each dNTP (not sure if my stock is 10 mM each dNTP or 10 mM total). To get 1 mM dNTPs, would add 8 uL of 10 mM dNTPs. (For 250 uM dNTPs (if stock is 10 mM each dNTP not total), add 2 uL of 10 mM). I think stock is 10 mM each dNTP (plus 2 uL 10 mM is significantly more than I added previously), so go with the lower amount). 

4. Run following program on thermocycler:
  - 98°C for 3 min
  - slowly cool (0.1°C per sec) to 25°C
  - 25°C for 5 min **ADD 5.5uL Klenow and 2uL 10mM dNTP here**
  - 25°C for 15 min
  - 75°C for 10 min
  - 12°C forever *but remember to start cleaning prior to it cooling off to discourage recovery of ssDNA*

Notes:
- Can slightly adjust incubation length with Klenow by adjusting at which point in 5 min at 25°C they are added. Add at beginning to increase time by a few minutes.
- Add Klenow product to DNA Clean and Concentrator DNA Binding Buffer while still warm to prevent any remaining ssDNA from forming secondary structures that will allow it to bind. 

5. Use Zymo DNA Clean and Concentrate kit to clean DNA and Nanodrop. Use 6 volumes of DNA Binding Buffer to capture small fragment. [Want to ensure everything binds, but don’t want to use 7 volumes as that may capture ssDNA.  Hopefully, adding warmed PCR product to buffer will prevent ssDNA binding.]

6. 6 volumes of DNA Binding Buffer for ~87.5 uL final volume is 526 uL. 
