# XC-Imperialism-Maps

![alt text](men%20d1.png "Logo Title Text 1") | ![](women%20d1.png "")
-|-
![](merged%20(4).gif "") | ![](men%20d3.png)

### About
This code is designed to be versatile to work in future seasons. It depends on tfrrs.org and lacctic.com to acquire the data. 
TFRRS disallows reproducing their data, so it is recommended to save the data locally and then download new files as needed
and append onto the current file. TFRRS reports all collegiate race results and presumably will not go anywhere in the foreseeable future.
LACCTiC is the work of a single person, so their is no guarantee the site will be available in the future. The website was used to determine 
which individuals comprised a varsity roster. If the site is not available in the future, these speed estimates could be recomputed
based on the downloaded TFRRS dataset.

For a team result to be counted, it must satisfy:
* Within the qualifying window (after X date)
* At least 3/4 of championship distance
  * 7.5k+ for men
  * 4.75k+ for women
* At least 3/7 of active varsity runners
  * Kolas criteria uses 4/7 @ regionals, but some teams may not run @ regionals. Some people may get hurt during the season or come back from injury, so 4/7 may be unobtainable

### TODO
* Create website via Github Pages to host an interactive version of the maps
  * Toggle by gender
  * Toggle by year
  * Toggle by week
  * On hover display relevant info
  * QUESTIONABLE
    * Dynamically load team logos
      * Locally for perennial teams
      * Or pull from 3rd party
    * Use appropriate team colours
      * I have a LUT for DI teams in a different repo
      * Other division data may not be accessible
      * Could generate based off logo
      * How to prevent conflict between adjacent similar colors?
