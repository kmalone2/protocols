# Protocol for Production of Lentiviruses

This protocol is for production of lentiviruses. Used most often by the [VEP DMS](../VEP_DMS/README.md) project. 

SPECIAL CONSIDERATIONS:

Importantly, you will be working with a BL2 agent. This means you should have at least a 1:20 working dilution of Wescodyne (located under the sink), and should sterilize *all* disposables with this Wescodyne solution while working. When you are finished with a plate, let it soak in Wescodyne for at least 10 minutes, then aspirate and tape closed. All waste is disposed of in the virus waste bin under the hood.

## Reagents needed:
- 6 well TC treated plate
- BioT transfection reagent
- DMEM (**NOT D10**)
- pHAGE2 helper plasmid mix
- 1 ug backbone plasmid 

The pHAGE2 helper plasmid mix is a 1:1:1:1 mixture of the following Bloom Lab plasmids:
1. [26 - HDM_Hgpm2](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/26_HDM_Hgpm2.gb)
2. [27 - HDM_Tat1b](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/27_HDM_tat1b.gb)
3. [28 - pRC-CMV_Rev1b](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/28_pRC_CMV_Rev1b.gb)
4. [29 - HDM_VSV_G](https://github.com/jbloomlab/plasmids/blob/master/genbank_maps/29_HDM_VSV_G.gb)

The mix is usually made such that it contains 250 ng of each helper per 5 ul of helper mix for 1 ug total of helper plasmid.

## Protocol
### Day 1
1. Seed cells in a 6-well plate. Seed HEK293T cells at a density of 4e5 cells per well.

### Day 2
BEFORE BEGINNING:
1. Ensure cells are 50-70% confluent
2. Best results are typically achieved if you gently change the media to fresh pre-warmed D10 a few hours before transfection.
3. Bring total volume of BioT needed to room temperature.

TRANSFECTION:

4. Make a master transfection mix:

Reagent | Volume per 1 reaction
---|---
BioT | 3 uL
| DMEM | 100 uL |
| pHAGE2 helper plasmid mix | 5 uL |
| backbone plasmid | 1 ug |

5. Incubate master mix at room temperature for 10 minutes.
6. Gently (dropwise) add to cells, ensuring even coverage across the well.

### Day 3
7. 18-24 hours post transfection, change the media to fresh D10 (as BioT is cytotoxic)

### Day 4 or 5
8. 48-72 hours post transfection, harvest lentivirus-containing supernatant. 
9. Collect the supernatant in a 5 mL syringe.
10. Attach a 0.45-µm syringe filter to the syringe. 
11. Into a cryo-tube, filter the lentivirus by pushing down on the plunger of the syringe. 
12. Aliquot as needed and store at 4˚C

### General Lentiviral Infection Protocol
Reagents needed:
- harvested lentiviral supernatant (can be freshly harvested)
- polybrene
  - the stock is at -20˚C and concentration of 10 mg/uL
  - working stock:
    - add 5 uL polybrene into 955 uL D10

Protocol, Day 1: 

1. The day before infection, seed cells for infection. Infection works better if the cells are sparse, so for hard-to-infect cells, such as MDCKs, you can seed as low as 1e4 cells per well in a 12-well dish.

Protocol, Day 2:

2. The day of infection, aspirate the media from cells to be infected. Ideally, cells are **<10% confluent**.
3. Add 900 uL harvested lentiviral supernatant from transfection.
4. Add 100 uL polybrene working stock (final concentration of 5 ug/uL)
5. 12-24 hours post infection, aspirate infection media and add 1 mL fresh D10
