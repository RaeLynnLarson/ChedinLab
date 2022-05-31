## DharmaFECT transfection of mammalian cells
[link to dharmafect protocol](https://horizondiscovery.com/-/media/Files/Horizon/resources/Protocols/dharmafect-kb-protocol.pdf)
### what is needed? 
| Plasmid | OD260 in ng/ul| amount needed for 2k ug transfection |
|--------|--------|-------|
| pFC19 | 385.8 |5.18 ul | 
| pFC30 | 1000 | 2 ul |
| pFC61 | 277.9 |7.19 ul |
| pFC66 | 106 | 18.86 ul |
| pFC9 | N/A | N/A | 
| GFP | N/A | N/A | 
### 2 to 4 micrograms of plasmid per a transfection. So for two of them I should probably make more of the four at least. Idk if I will actually need it, but that depends on how many rounds we do. Perhaps we get the first round done, watch for variation, and then make more if needed.
### pFC9 (or any pEH plasmid) can work as negative control since they have no mammalian promoter, only phage. Possit#ive control is weird, but maybe GFP could work to check that plasmid is getting into the cell. Possibility it could gunk things up tho, so perhaps look into past papers. Collin has GFP that might work. 
[^1] PCR reaction inside cell sometimes needs help via primers. A 2-3 kb needs to be flanked by 500 bp primer prior to transfection. Ethan is going to design these because he needs to put a special code in that will determine if we did the transfection right during sequencing. 
### Ingredients 
- [ ] 2 to 4 grams plamsid, including pFC19, pFC30, pFC61, pFC66, pFC9, and GFP 
- [ ] 6 (at least) 100 mm x 10 cm plates 
- [ ] lots of hygromycin (200 ug/mL) 
- [ ] serum-free growth media 
- [ ] DharmaFECT kb reagent 

### Steps: 
- [ ] dillute cells in 10 uL serum-free growth media
- [ ] gently mix DharmaFECT kb reagent via pipetting. Dilute reagent in 10 uL per plate serum-free growth media 
- [ ] Add 10 uL dilute reagent to 10 uL dilute DNA for 20 uL solution. Incubate this for 10 min at room temp 
- [ ] add 80 uL growth media to complex and mix 
- [ ] get cell culture plate (must be at 70-90% confluent) and aspriate media. Then add 100 uL of tranfection reagent:DNA complex 
- [ ] rock plate to acheive even distrubtion of complex across cells 
- [ ] after first 48 hr, add medium containing antibiotic (200 ug/mL) 
- [ ] Check cells every day or so to see if any GFP expression occured. This will be our indicator of tranfection efficacy. 

#### 5-24-22 
- Cell transfection occured Friday with no significant problems. Hygromycin was added Saturday, and then expression was checked Tuesday (today). Cells show high confluency and low transfection rate (shown below). 
[GFP-rh1-hek293c18-transmission.pdf](https://github.com/RaeLynnLarson/ChedinLab/files/8766204/GFP-rh1-hek293c18-transmission.pdf)
[GFP-rh1-hek293c18-confluency.pdf](https://github.com/RaeLynnLarson/ChedinLab/files/8766205/GFP-rh1-hek293c18-confluency.pdf)

#### 5-31-22 
-transfecting cells today. Used 4k ng of DNA per a transfection. 
.+
| Numeral | Plasmid | OD260 in ng/ul| amount needed for 4k ng transfection |
| ------- |--------|--------|-------|
| I | pFC9 | 593 (10x dill.) | 6.74 ul | 
| II | pFC61/66 | 5045 (10x dill.) | 1 ul |
| III | pFC61/66 | 495 (10x dill.) | 10 ul |
| IV | pFC19 | 351 | 14.24 ul |
| V | pFC30 | 1152 | 4.34 ul |
| VI | GFP | 266 | 18.8 ul | 

- [ ] aspirate media and add 9.5 mL penstrep/strep free media 
- [ ] get two sets of 1.5 mL tubes, and put 240 uL OptiMEM both 
- [ ] in one set of tubes, add 1:1000 (10 uL) tubofectamine (stock) and the other add 4 ug plasmid
- [ ] flick to mix (around 20x) and then incubate for 5 min (this time is so short just leave it during the nxt step)
- [ ] Combine tubofectamine and plasmids, mix (simile) 
- [ ] incubate for 20min at RT
- [ ] add mixture to plates. Expression should happen 24 to 48 hrs later
