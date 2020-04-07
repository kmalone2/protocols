# Protocol for DMS Library Scale Yeast Transformation

Submitted by Tyler Starr. 

This protocol has typically yielded me ~5-10 million cfus when transforming pETCON-type plasmids into AWY101 yeast strain. Volumes can be scaled up (or multiple tubes easily accommodated) to get another 10-fold boost if needed

Note: one of my yeast libraries ended up with highly skewed variant coverage, and my prediction that this occurred due to unequal initial growth rates during the transformation outgrowth step in liquid culture. We could consider plating cells on large petri dishes as we do with bacterial libraries. If doing this, one thing to consider is that yeast auxotrophic markers (i.e. they require an enzyme for Trp synthesis to come from the plasmid) are a sort of weak selection when large numbers of cells are plated – my guess is because yeast can scavenge Trp from the dead cells around them on the plate. Furthermore, colony sizes on yeast plates don’t seem to be as uniform as on bacterial plates, so I’m not sure whether this strategy would work for yeast. Anyway, this might be worth trying, but could require some optimization.

Another note: At least when I used to do electroporation of library plasmids into yeast, I had many multiple vector transformants. Papers e.g. “Quantifying and resolving multiple vector transformants in S cerevisiae plasmid libraries” highlight this effect. Multiple passage steps prior to functional selection are important to allow these multiple vector transformants to resolve out.

## Reagents Needed

- YPD (500mL) liquid and agar media
	- 10g bacto peptone
	- 5g yeast extract
	- (12g bacto agar for plates)
	- To 450mL with water
	- Autoclave
	- While cooling, add 50mL sterile 20% glucose
	- (For YPAD, add 20mg powdered adenine hemisulfate prior to autoclave)
- 2x YPAD (500mL):
	- 20g bacto-peptone
	- 10g yeast extract
	- 40mg adenine hemisulfate
	- Fill to 400mL with H2O, autoclave liquid cycle
	- Add 100mL 20% dextrose
- SD-CAA selective growth media (500mL)
	- 3.35g YNB
	- 2.5g Casamino acids
	- 1.065g MES
	- (12g agar for plates)
	- Bring to 450mL H2O
  - (Check that pH hits 5.3 – exact pH not important since not buffered – I believe you just want media acidic to inhibit bacterial contamination)
	- Autoclave
	- While cooling, add 50mL sterile sugar solution (20% Dex for SD-CAA) (or add for each use,)
- Salmon sperm DNA (carrier DNA for yeast transformation)
	- 250mg ssDNA
	- 125mL sterile 1xTE
	- Break up by pipetting with large bore 50mL pipette
	- Stir at 4˚C overnight
	- Aliquot and freeze -20˚C
- 1M LiAc (100mL)
	- 10.2g lithium acetate
	- 100mL H2O
	- Autoclave (15min) or sterile filter
- PEG MW 3350 50% w/v (100mL)
	- 50g PEG 3350
	- Add ~30mL H2O, stir in beaker to dissolve (can use gentle heat)
	- Bring to 100mL with H2O
  - Sterile filter (takes a while!)
	- Store RT, well capped! (Evaporation bad)
  
## Protocol

### Cell Prep

Scaled for up to three library transformations!

### Day -2
1. Restreak yeast strain (e.g. EBY100 or AWY101 for yeast display) from glycerol stock onto YPD agar plate (or use a previous restreak kept at 4oC, up to two months or so in fridge are generally fine. For a library I might try for a reasonably fresh restreak, e.g. couple of weeks)

### Day 1
2. Start 25-mL 2xYPAD overnight with a single colony of untransformed yeast in 250mL baffled flask (start early/mid afternoon)
3. Put 100mL 2xYPAD at 30oC to prewarm overnight

### Day 2:
4. Read O/N OD with 1:50 dilution:
5. Spin 66.7 OD*mL units 3min 3krpm, aspirate or pour sup
6. Resuspend to 100mL in prewarmed 2xYPAD (0.67 OD) in 1L baffled flask
7. Incubate 30oC ~3.5-4 hours, to OD 2.67-3.3
8. While growing
   - denature 500uL ssDNA per transformation, 5min 95C on heat block or on thermocycler, chill on ice
   - Set water bath 42oC (setting to about 44.4oC on the temperature dial yielded 42oC bath)
   - Prepare transformation reagents, one set of the following for each library (if doing positive and negative control, also prep at 6x reduced volumes):
      - 50ug library plasmid in 340uL total volume using sterile water (1.6ug in 56.7uL for controls)
      - Transformation mix:
         - 2.4mL 50% PEG3350
         - 360uL 1M LiAc
      - Recovery mix:
         - 13mL SD-CAA
         - 13mL 20% Dextrose
      - Outgrowth flask
         - 1L flask with 100mL SD-CAA
9. After cells grown to scale, spin 83 OD*mL of cells per library (13.83 OD*mL for controls) in 50mL conicals, 4k rpm 5 min, pour out sup
10. Wash with 25mL sterile water two times (4.2mL for controls), spinning 4k rpm 5min, aspirating sup

### Transformation
11. Resuspend cell pellet in 500uL salmon sperm DNA (83.3uL for controls)
12. Add 340uL sterile water including 50ug DNA (56.7uL controls)
13. Add yeast/DNA mixture to pre-prepared Transformation mix in 15mL conical, swirl gently to mix
14. Incubate 35min in 42oC water bath, swirling tube gently to mix every 6-7 minutes
15. Dilute transformation mix into room temp recovery mix
16. Spin down cells 3k rpm 5min, aspirate sup
17. Resuspend into 100mL SD-CAA in 1L baffled flask, incubate 30oC shaker 225rpm (should be starting OD of ~0.83, minus cell loss) overnight for post-transformation outgrowth
   - For positive and neg ctrl, resuspended pellet to 2mL and plate 100uL directly

### Yield and outgrowth
18. Plate 100uL of 10-1, 10-2 dilutions on SD-CAA plates to estimate yield, incubate 30oC 2 days, count colonies to estimate transformation yield. If you just want to make sure there are >1e6 transformants and don’t care much about yield beyond that, 10-1 dilution should be sufficient (100 colonies on 100uL plated of 10-1 dilution corresponds to 1e6 transformants)

### Day 3:
19. In AM, check outgrowths have grown (e.g. at 10am, OD was 4.4 for an example successful transformation)
20. Spin 100 OD*mL 5min 3k rpm, resuspended to 100mL in fresh SD-CAA, incubate ~8+ hours
21. Spin 18.5 OD*mL aliquots (~1e8 cfu according to my calibration curve plating to count cfu versus our nanodrop spec OD), resuspend in 1.5mL 25% glycerol in media, and flash freeze in dry ice/EtOH bath or liquid nitrogen. Store aliquots -80oC
