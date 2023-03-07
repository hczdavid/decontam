## Documentation

This repository implements the hypothesis testing method to identify contaminants, including tcontam for high microbial biomass and tcontamL for low or mixed microbial biomass. 

## Installation

To install the decontam R package with the tcontam and tcontamL implementation, you need to install through the Github using the `devtools` package:

```S
library(devtools)
devtools::install_github("hczdavid/decontam")
```
## Analysis
We demonstrate the usage of tcontam and tcontamL, and compare the performance with current decontam method using simulation and two real microbiome datasets.

[Oral microbiome dataset analysis](http://htmlpreview.github.io/?https://github.com/hczdavid/tcontamManuscript/blob/main/analysis/oral%20microbiome%20dataset/oral_data.html)

[Dilution dataset analysis](http://htmlpreview.github.io/?https://github.com/hczdavid/tcontamManuscript/blob/main/analysis/dilution%20dataset/dilute_data.html)

[Simulation analysis](http://htmlpreview.github.io/?https://github.com/hczdavid/tcontamManuscript/blob/main/analysis/simulation/simu_analysis.html)





## Other Resources

Bugs and difficulties in using decontam are welcome on [the issue tracker](https://github.com/benjjneb/decontam/issues).

Planned feature improvements are also publicly catalogued at on the "Issues" page for decontam: https://github.com/benjjneb/decontam/issues
