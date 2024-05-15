# Smart TV Automatic Content Recognition (ACR) Analysis

This repository is dedicated to the analysis of Automatic Content Recognition (ACR) technology on two popular smart television brands: LG and Samsung. The aim is to delve into how these TVs implement ACR and understand their behavior through experimentation and analysis.

Contents

`trigger_validation_scripts`: This folder contains scripts for conducting experiments to automatically test different functionalities of the TVs. The primary script, experiment.sh, automates the process of turning on the TV, capturing network traffic for a specified duration, and then turning off the TV. During the experiment, manual interaction may be required to perform specific actions on the TV, such as opening Netflix. This script additionally checks whether the experiment is successful by checking the size of the generated pcap file.

`analysis_scripts`: Here, you'll find scripts designed to extract meaningful insights from the captured network traffic (pcap files) and comprehend the behavior of the television sets.

**Usage**

To run the experiments, follow these steps:

Navigate to the trigger_validation_scripts directory.
Execute the experiment.sh script with the following parameters:

`./experiment.sh <.txt file of the TV> <time duration of the experiment>`

Replace <.txt file of the TV> with either `exp_lg.txt` or `exp_samsung.txt`, depending on the TV brand you want to analyze.
Replace <time duration of the experiment> with the desired duration of the experiment in seconds.


The collected .pcap files are available at these links:

UK - Samsung `https://osf.io/y7svd/?view_only=695d9733356a44889160f8a3d55da684`

UK - LG `https://osf.io/768t2/?view_only=508a817405e04d07978593d0ae4ff00c`

US -Samsung `https://osf.io/kqw2p/?view_only=b5bff609bbf745f0b9d3d89265d2dbe6`

US - LG `https://osf.io/2p6ar/?view_only=aae99015580241c9a1877d3ba3d63e12`

