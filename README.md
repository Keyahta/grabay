# grabay
Indoor localization dataset 

cite the dataset :[![DOI](https://zenodo.org/badge/518760524.svg)](https://zenodo.org/badge/latestdoi/518760524)

The HUSTData is from a typical lecture building with a total area of 482m2 in our university. We did not place our own APs. Instead, we employed the existing WiFi infrastructure with APs deployed by different parties, such as individual laboratories, telecom operators, and campus authorities. Indeed, the total number of hearable AP in our experimental environment was more than 400, while, for each sample, normally more than 70 APs can be heard. We note that
employing the existing WiFi infrastructure makes our proposed scheme ready to be implemented in many practical scenarios. Huawei Honor 3C smartphone was used to collect RSS samples. In total, 13,370 samples were collected for training,and the test set contains 5600 samples uniformly distributed in the whole environment. Note that the samples are firstly annotated with true location information at collection. That is, we used site survey for calibration. To emulate annotation errors, we again annotate each sample into a new location with a location offset randomly drawn from a Gaussian distribution with zero mean and σ = 0.6m, and σ = 1.2m standard deviation.
