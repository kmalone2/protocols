# Protocol for 96-well Minigenome Transfections

Submitted by Rachel Eguia.

Note:
Schedule flow machine in advance to ensure you have a slot. I typically book 1-2 hrs for the plate flow just to be safe. 
•	The machines that will work for GFP and mCherry in a 96-well plate format are the LSR, Fortessa, or the Symphonies

Download included spreadsheet for calculations!


## Reagents Needed

- BioT 
  - Here I’ve attached the BioT website with the numbers for scaling up the transfection into a 96-well plate: http://bioland-sci.com/index.php?main_page=page&id=27
  - It’s the same general protocol as a normal transfection with some key differences that I use in my spreadsheet:
  - Total ng per well = 100 ng
  - BioT per well = 0.15 uL
  - Volume of transfection media = 5 uL
- TC-treated 96 well plate (V-bottom and flat bottom)
- D10


## Protocol

### Day -1

1.	Count cells and dilute to give a concentration of 25e4 cells/mL. 
2.	Pipette 100 uL of this cell concentration into each well of a 96-well V-bottom plate using a multi-channel to give a seeding density of 2.5e4 cells/well and incubate at 37C until transfection (I usually plate cells the day before my transfection)
  - V-bottom plates have worked well for me in the past— the tapered end allows a nice pellet to form so you won’t have to worry as much about sucking up your cells

### Day 0

Overview: Will prepare transfection master mixes and complexes in a separate 96-well plate and then use a multi-channel pipette to add complexes directly onto the cells you plated yesterday. I have designed a spreadsheet that can be used to calculate the amounts of each polymerase plasmid that you need for the amount of samples and number of replicates for the master mixes.  

BioT Minigenome Calculations Excel Spreadsheet: So basically, I’ve formatted it so you just put in the ng/uL of each plasmid and it calculates how many uL to add to the master mix. You can then mix this in a 1.5 eppy. Then I would take it into the TC room hood, add the serum-free DMEM, and add the calculated amount of master mix to the top rows of an empty 96-well dish in the same configuration that you want the samples to be in your actual plate. Just mimicking the wells of the plate with cells in it. 
Note: on my spreadsheet I have included the replicates in the MM calculations. I usually perform the assay in triplicates to make sure my technique is good, but you can change it to just 2 replicates if you want.

3.	Make Master Mix (MM) containing volumes of each of the following (calculated using the BioT Minigenome Calculations excel spreadsheet):
  - Polymerase plasmids (PB1, PA, and NP)
  - pcDNA-mCherry plasmid (1505)
  - pHH-PB1-EGFP (208)
  - Serum-free DMEM media
4.	Mix MM thoroughly by pipetting
5.	Divide up the MM for each PB2 mutant being tested
  - This will differ depending on the nature of experiment— 6 different PB2s, you’ll split MM into 6 tubes 
6.	Add PB2 mutant plasmid as calculated by the spreadsheet (you will have to dilute each plasmid so that they are all at the same concentration— which makes your life easier when you’re using the multichannel and wanting to split the wells equally)
7.	Add total amount of MM+PB2 into top wells of a non-tissue culture treated 96-well plate 
8.	Don’t forget to make single-color controls! A guide for this is also on the excel spreadsheet. I usually make a master mix for the controls and then split it before adding the GFP and mCherry plasmids.
9.	Once everything has been added to the set-up plate, you can now add the BioT. To avoid pipetting small volumes, I will dilute the BioT in DMEM and add 1 uL of that into each well.
10.	If performing technical triplicates, I add the BioT first, incubate for 15-20 minutes to allow the transfection complexes to form, and then split the transfection samples onto my cells. 
11.	Pipette transfection samples into 96-well plate seeded with cells using a multichannel 
12.	Incubate cells at 37 C in CO2 incubator for 24 hrs

### Day 1

Flow prep usually takes me about 30-45 minutes so plan accordingly
13.	Prepare PBS + 1% BSA and place on ice
14.	Remove supernatant by pipetting with multichannel. I usually tilt the plate and pipette from the side of each well to make sure I don’t disrupt the cells.  
15.	Add 50 uL trypsin to each well, incubate until cells detach from wells 
16.	Quench trypsin by adding 125ul D10 to each well using multichannel. Pipette up and down multiple times to break up any cell clumps 
17.	Spin plate at 400 x g for 4 minutes
  - Visualize pellets under the microscope because sometimes the pellets don’t form directly in the middle of each well— sometimes they’re near the top or bottom of the wells. If this is the case, just make a note so that when you go to remove the supernatant you place your pipette on the correct part of the well.
18.	Remove supernatant by pipetting with multichannel being careful not to suck up your cell pellets (see above)
19.	Resuspend cells in 200 uL of your cold PBS + 1% BSA solution, pipetting thoroughly to break up clumps and produce a single-cell population
20.	Take the no-color control and single-color control cells out of the plate and pipette into their own cell strainer tubes. This makes it much easier to set voltages during your flow appointment. The techs down at the flow core will ask you to do this anyway, so they will greatly appreciate it and it’ll save you time during your appointment
21.	Keep plate on ice and covered with tinfoil until flow appointment 
  - Not sure if the tinfoil is completely necessary, but I figured it is good practice to keep samples with fluorescence in the dark 
22.	Set up the flow machine to be able to read a plate (this can be a lot so I usually just ask one of the people down at the flow core to help me out).  


