## wget: Setting Download Method to "wget -c"


Loading this package will change the default behavior of 'download.file'. The download method will be changed to using "wget -c" so that continued downloading will be supported. User can run 'wget_unset()' to disable it.

All platforms including Linux, MacOS and Windows are supported.


----

What you need is to load the package by `library(wget)`. Then `download.file()`, `install.packages()` and `BiocManager::install()` will all support continue retrival.

see also <https://mp.weixin.qq.com/s/z2ceLeSel1m8uxuNb1px3g> (in Chinese).

You can load the `wget` package at R startup by adding the following command to `~/.Rprofile` (`~/Documents/.Rprofile` if in Windows).

```r
library(wget)
```

![](inst/figures/2020-04-27_11-01.png)
