## Background 
#### EBV is a viral vector that can get into the chromatin and replicate in mammalian cells. We will be using it to transfect a number of cells with R-loop prone plasmids an see how, and where they form R loops 
#### R-loops can get into chromatin and make R-loops as long as it is in the correct orientation (Chedin. 2012). 
#### We are going to use HEKI 293c18 cells. These are resistant to both Amp and Hygromycin and so we will use 200 ng/ml hydromycin buffer to grow out cells in 
#### After cells are transfected with plasmids, will will use Hirt Harvest to harvest DNA. 
####  After that, SMRF seq can be used to determine location of R-loops 
# Prep of materials 
## plasmids used 
| Plasmid | OD260 in ng/ul| amount needed for 1,5k ng transfection |
|--------|--------|-------|
| pFC19 | 385.8 | 3.888 ul |
| pFC30 | 1000 | 1.5 ul |
| pFC61 | 277.9 | 5.4 ul |
| pFC66 | 106 | 14.15 ul |
### plasmids were OD260nm'ed and the results are shown above. 
### Samples where then digeted with 0.5 ul ECORi and 1 ul 2.1 NEB buffer for >20 min at 37 C. After that the samples were gel electrophoresised in 0.8x gel at 70 V for > 30 min. 1 kb ladder was provided 
### all plasmids in the past show R-loop under phage promoter
![plasmids after digest on gel!](C:\Users\rchll\Downloads\School stuff.jpg "3-22-22")
#### Note: the image above shows no smear on the bands, showing little to no DNA degredation during storage. This is important because this DNA was quite old (~20 yrs) and was in cold storage. The first vial (second lane) shows less product than the rest of the lanes. This has been chalked up to sampling error due to the age of the DNA  

# Overview: 
## Questions: what will happen when we increase the plasmid size from the normal 3.5kb to 10x increase (both supercoiled at same density). If R-loops are there to relax supercoils, we should see an increase in supercoils. Do R-loops have a size limit? (# of supercoils affect the length, number, and formation of R-loops). This will be the in vivo side of the experiment to compare to the in vitro side. 
## Procedure: Take the HEK cells and we transfect them with plasmids. after growth we collect the DNA with HIRT harvest. Then we run the plamsids on a gel/clean and control. then we use SMRF seq to find the R loops. 
## controls: pFC9 (or any pEH plasmid) can work as negative control since they have no mammalian promoter, only phage T7 promoter sensewise and a T3 promoter antisense wise. For possitive control we can check that things are working by seeing if a simple GFP works. If the cells light up in the nucleus, we know we transfected them properly  
