Dynasty Super Patch v8

v8 Updates

This patch allows for PAC12 Championship game textures to used

v7 Updates

This patch fixes the BCS Bowl Alignments with the right conferences, something that wasnt possible before with the old method of doing this, but with the schedule generation built-in, this works like a charm. But I didn't know until now.

So this method hopefully will fix your dynasty save. There is a new dynasty save starter kit now available, but this is for those who want to patch in-progress. This is a one-time patch only!


First off, BACKUP YOUR SAVE!!

Do this during the off-season as well!! Or worst case, do it BEFORE bowl games are scheduled, ideally at week 1. 


First step is to get the save out using a combination of MyMC and PS2 Save Builder.

1. Load up MyMC and find your Memory Card virtual file.
2. Export the Dynasty Save.
3. Open the Dynasty Save in PS2 Save Builder, and highlight, and extract the first file. It should be start with BALSUS.


Next is to use a combination of Madden Xtreme DB Editor and CSV files to fix the save.


1. Open up MXDBE and load the BALSUS save.
2. Click BOWL. RIGHT-Click on any of the table headers, and choose ADDENDUM. 
3. Find the Bowl-addendum.csv file and import it in. This should update the bowl matchups. Rose Bowl should now show BCI1 as 1 and BCI2 as 10.

4. Click CONF. Import CONF.csv  Big Ten should be 1 for CGID
5. Click DIVI. Import DIVI.csv  Big Ten should be 1 for CGID
6. Click TEAM. RIGHT-Click on any of the table headers, and choose ADDENDUM.
7. Find TEAM Addendum v3.csv and import it in. Wisconsin's CGID should be 1.

8. File and SAVE.

Now you need to import the data back in by doing the first section in reverse. 

That is all!

