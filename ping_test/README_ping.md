# Readme


## Requirements

* tidyverse
* rmarkdown

`Rscript requirements.R`


## Adaption

* Server locations `ping_test.Rmd` line 27. The first entry should be your router, which may be `192.168.1.1` or similar.
* Test duration `ping_test.Rmd` line 40
* Sample interval `ping_test.Rmd` line 39
* Consider changing the output file name to describe your current setup (e.g. vpn) `make_ping.R` line 7

## Running

cd to dir, then:

`Rscript make_ping.R`
