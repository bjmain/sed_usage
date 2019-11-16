# sed_usage
### GCTA was designed for human samples so it breaks if you have more than 23 chromosomes.
#### For my analysis, I needed to replace 0th chromosome with an arbitrary 2.
sed 's/0/2/'

##### If you want to replace all 0's, add g after the last bracket. Or if you want to replace the 2nd occurance on each row: add 2.
