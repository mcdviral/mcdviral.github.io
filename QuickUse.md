---
sort: 5
---

# Quick Use

## SLAM 

We assume that you have downloaded the rosbag files to a folder `/path/to/MCD` as in [Fig. 1](#data-organization):

<figure style="float: right; margin-left: 10px;">
  <img src="images/data_path.png" alt="Description of the image">
  <figcaption id="data-organization">Fig. 1: Recommended organization of MCD data.</figcaption>
</figure>

Below are some SLAM methods that have been benchmarked on MCD. Please follow the installation instructions at each repository. After compiling, modify the `data_path` argument in the `run_mcdviral.launch`. Hence, you should be able to launch the experiment on an sequence MCD by `roslaunch fast_lio run_mcd.launch`.

* FAST_LIO: [https://github.com/brytsknguyen/FAST_LIO](https://github.com/brytsknguyen/FAST_LIO)
* SLICT: [https://github.com/brytsknguyen/slict](https://github.com/brytsknguyen/slict)
* CLIC: 