# Compiled R packages 

# RHEL 8 and R 4.1.3

An AWS ec2 instance running RHEL 8 was used for this.

The packages were installed from R 4.1.3 and the installation 
location is found from the `.libPaths()` function in R

```
> .libPaths()
[1] "/home/ec2-user/R/x86_64-pc-linux-gnu-library/4.1"
[2] "/opt/R/4.1.3/lib/R/library"
```

The files in `/home/ec2-user/R/x86_64-pc-linux-gnu-library/4.1` were copied here.

Note that this repository uses Git LFS: https://git-lfs.github.com/

# References
* https://docs.rstudio.com/resources/install-r/
