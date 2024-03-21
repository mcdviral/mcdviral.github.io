---
sort: 6
---

# Semantic Segmentation Tutorial

<figure style="float: right; margin-left: 10px;">
  <img src="images/data_path.png" alt="SLICT CONFIG" style="width: auto; height: 300px;">
  <figcaption id="data-organization">Fig. 1: Recommended organization of MCD data.</figcaption>
</figure>

We assume that you have downloaded the rosbag files to a folder `/path/to/MCD` as in [Fig. 1](#data-organization):

We try to create a consistent settings for the benchmark. Specifically, after compiling the code successfully, one only needs to seek out the `run_mcdviral.launch` file, modify the `data_path` and `bag_file` arguments, and then launch the method with `roslaunch <method> run_mcdviral.launch`. Some extra configurations for each method will also be noted.
