<!-- <p align="center">
    <img src="images/maps_whitebackground_.png" alt="maps_and_elevation" width="98%"/>
</p> -->

# [MCD VIRAL: Visual-Inertial-Ranging-Lidar Multi-Campus Dataset](https://mcdviral.github.io)

The dataset is collected from hardware suites featuring the following sensors:

* 3D spinning lidar
* Epicyle pattern lidar
* Stereo cameras
* Multiple IMUs
* UWB nodes.

Besides featuring a big set of sensors, we also capture the dataset over large-scale campus areas in Asia and Europe.

# Updates

**14/02/2023**: Preliminary release.

# Downloads

There are 18 sequences captured in as rosbags compressed with bz2 method. We split the data into different bags based on the sensor type. User can freely select the combo that suits their interest. (To play all bag files under the same folder, one can use the `*` symbol, for e.g. `rosbag play ntu_day_01/*.bag`)

It is recommended that user reads through the [notes](Sensors.html) on each sensor to use the sensor data correctly.

*(Note: Currently only ntu_day_01 sequence is accessible. Others are under development.)*

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-11ai{background-color:#ffffff;color:#330001;font-weight:bold;text-align:center;text-decoration:underline;vertical-align:top}
.tg .tg-vu6z{background-color:#ffffff;color:#330001;text-align:center;text-decoration:underline;vertical-align:top}
.tg .tg-s527{background-color:#ffffff;color:#330001;text-align:center;vertical-align:middle}
.tg .tg-mypc{background-color:#ffffff;color:#330001;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-5hi3{background-color:#ffffff;color:#330001;text-align:center;text-decoration:underline;vertical-align:middle}
</style>
<table class="tg" style="undefined;table-layout: fixed;">
<colgroup>
<col style="width: 130.75px">
<col style="width: 280.75px">
<col style="width: 120.75px">
<col style="width: 120.75px">
<col style="width: 120.75px">
<col style="width: 120.75px">
<col style="width: 120.75px">
<col style="width: 120.75px">
<col style="width: 120.75px">
<col style="width: 120.75px">
</colgroup>
<thead>
  <tr>
    <th class="tg-mypc">SeqID</th>
    <th class="tg-mypc"><span style="font-weight:bold">Ground Truth</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">D435i</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">D455 bottom</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">D455 top</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">Livox</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">Ouster</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">UWB</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">VN100</span></th>
    <th class="tg-mypc"><span style="font-weight:bold">VN200</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1k5nQ81_1nA1Ng8IlQ1SghwBNmIUgbS0o" target="_blank" rel="noopener noreferrer">kth_day_06 (42.8 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="kth_day_06_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1kZZhhqXT_pXLvLhlfGl5Ip4XpLCHF6_e" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1kZZhhqXT_pXLvLhlfGl5Ip4XpLCHF6_e" target="_blank" rel="noopener noreferrer">(16.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1j_SfAzs3jZJOUmV-DA11Ixrln00pNb5x" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1j_SfAzs3jZJOUmV-DA11Ixrln00pNb5x" target="_blank" rel="noopener noreferrer">(16.1 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1X1fAdHPMXN5oYhtT6VsSZIppzTe9Ttda" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1X1fAdHPMXN5oYhtT6VsSZIppzTe9Ttda" target="_blank" rel="noopener noreferrer">(778 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1DHpRSoY5ysK1h2nRwks_6Sz-QZqERiXH" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1DHpRSoY5ysK1h2nRwks_6Sz-QZqERiXH" target="_blank" rel="noopener noreferrer">(9.6 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1a2o-vQFK0vC0QqbXyM41BnzSNH9VkQ6N" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1a2o-vQFK0vC0QqbXyM41BnzSNH9VkQ6N" target="_blank" rel="noopener noreferrer">(1 MB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1cf_dmcFAX9-5zxB8WcFVc3MaVNczEMqn" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1cf_dmcFAX9-5zxB8WcFVc3MaVNczEMqn" target="_blank" rel="noopener noreferrer">(56 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/17bE6-s3QjB7JJlmPYNLsJkTQgnHTeEyr" target="_blank" rel="noopener noreferrer">kth_day_09 (23.4 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="kth_day_09_gt" width="186" height="112"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1fGxxe5JGvkNC-BVyHeLdLfdTNkhTPC9i" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1fGxxe5JGvkNC-BVyHeLdLfdTNkhTPC9i" target="_blank" rel="noopener noreferrer">(7.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1yyrmxYYENBe5jmsfH6vONhvywB71Tzf8" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1yyrmxYYENBe5jmsfH6vONhvywB71Tzf8" target="_blank" rel="noopener noreferrer">(7.1 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1LLEbZ244oicynIL4gjin7251ceo6IAgQ" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1LLEbZ244oicynIL4gjin7251ceo6IAgQ" target="_blank" rel="noopener noreferrer">(687 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1mhMpwr3NDYfUWL0dVAh_kCTTTLFen31C" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1mhMpwr3NDYfUWL0dVAh_kCTTTLFen31C" target="_blank" rel="noopener noreferrer">(8.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1yR9vVANK8jT5L35R3ilgI8ChDnA2nzhl" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1yR9vVANK8jT5L35R3ilgI8ChDnA2nzhl" target="_blank" rel="noopener noreferrer">(1 MB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/16j2Ud99lrgkNtIlPQ_OV6caqZZc-bHA-" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/16j2Ud99lrgkNtIlPQ_OV6caqZZc-bHA-" target="_blank" rel="noopener noreferrer">(48 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1bhGBi9DqoCxtqY3hbz666kCBuxVIwXQT" target="_blank" rel="noopener noreferrer">kth_day_10 (27.1 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="kth_day_10_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1ww7LdYTnWgsQJ5YI4YgCkvdjIQBBn9Vp" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1ww7LdYTnWgsQJ5YI4YgCkvdjIQBBn9Vp" target="_blank" rel="noopener noreferrer">(10.0 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1X2Sbzm-zFKhE7MW9-dNJrv-2eyD2iFuh" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1X2Sbzm-zFKhE7MW9-dNJrv-2eyD2iFuh" target="_blank" rel="noopener noreferrer">(9.9 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/19BiksWKakCinCq9FuYf203RY620R32cI" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/19BiksWKakCinCq9FuYf203RY620R32cI" target="_blank" rel="noopener noreferrer">(525 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1NbOHfVaCZkXPz28VwLrWLfITXYn25odh" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1NbOHfVaCZkXPz28VwLrWLfITXYn25odh" target="_blank" rel="noopener noreferrer">(6.7 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1Nf5odmAA6sGTPXGBw-h4fR4_VoBDjwJ6" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1Nf5odmAA6sGTPXGBw-h4fR4_VoBDjwJ6" target="_blank" rel="noopener noreferrer">(876 KB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/13qyhDyrj6doa7s0cdbtF1e_Bh-erFMUv" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/13qyhDyrj6doa7s0cdbtF1e_Bh-erFMUv" target="_blank" rel="noopener noreferrer">(38 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1YZTvQ1QI86HW8C7Ifq6VFC02fQRtMMCw" target="_blank" rel="noopener noreferrer">kth_night_01 (43.5 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="kth_night_01_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1xouzt8EHb9IlO_koXr_VsCwLh7qhUjyD" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1xouzt8EHb9IlO_koXr_VsCwLh7qhUjyD" target="_blank" rel="noopener noreferrer">(14.5 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1dQ1EgGcMePdEfXrtXyjVvyWgZSgVFNJz" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1dQ1EgGcMePdEfXrtXyjVvyWgZSgVFNJz" target="_blank" rel="noopener noreferrer">(17.9 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1jWp2THLV2v51a7APTUhbqVCH7z6Crtg_" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1jWp2THLV2v51a7APTUhbqVCH7z6Crtg_" target="_blank" rel="noopener noreferrer">(855 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1mbLMoTPdhUI9u-ZOYFQJOYgrcQJb3rvN" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1mbLMoTPdhUI9u-ZOYFQJOYgrcQJb3rvN" target="_blank" rel="noopener noreferrer">(10.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1zIHjLy7iHt_VgjHVw5zmIXz6x_g4lMRB" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1zIHjLy7iHt_VgjHVw5zmIXz6x_g4lMRB" target="_blank" rel="noopener noreferrer">(1 MB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1RMfF_DYxUkP6ImwCK039-qJpzbGKw_m7" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1RMfF_DYxUkP6ImwCK039-qJpzbGKw_m7" target="_blank" rel="noopener noreferrer">(60 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1GJ2ZGsBBwiYY3DHk0XCE9cwV2s-xdM7a" target="_blank" rel="noopener noreferrer">kth_night_04 (14.9 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="kth_night_04_gt" width="270" height="162"></td>
    <td class="tg-5hi3">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/15NtThX00mL6FIE_pvmoqkYTCisnZ9Ao2" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/15NtThX00mL6FIE_pvmoqkYTCisnZ9Ao2" target="_blank" rel="noopener noreferrer">(3.2 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1HhsSyflVhO1JwOwgiVQv4f39kqRku4RK" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1HhsSyflVhO1JwOwgiVQv4f39kqRku4RK" target="_blank" rel="noopener noreferrer">(3.2 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1T4rM9bnsOybm4C24pv4V8SHPOQQGEBMc" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1T4rM9bnsOybm4C24pv4V8SHPOQQGEBMc" target="_blank" rel="noopener noreferrer">(650 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1SRMbAu1UyA4lJB4hZdmY-0mic-paGkKF" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1SRMbAu1UyA4lJB4hZdmY-0mic-paGkKF" target="_blank" rel="noopener noreferrer">(7.8 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1XLa2JYsJi5hzHb9trlvpuYot-M-aqCY6" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1XLa2JYsJi5hzHb9trlvpuYot-M-aqCY6" target="_blank" rel="noopener noreferrer">(1 MB)</a></td>
    <td class="tg-5hi3">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/10KIUpaJIID293P3um8OfWWiiQ1NArj2o" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/10KIUpaJIID293P3um8OfWWiiQ1NArj2o" target="_blank" rel="noopener noreferrer">(47 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1yK8xOTgZCiWCxcR_lVMKSfVwkgm5XYso" target="_blank" rel="noopener noreferrer">kth_night_05 (14.2 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="kth_night_05_gt" width="270" height="162"></td>
    <td class="tg-5hi3">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1YD0s995Js23-en4NDvaHO_ifnfEnPdCq" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1YD0s995Js23-en4NDvaHO_ifnfEnPdCq" target="_blank" rel="noopener noreferrer">(3.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1lWzl2fnOGrnXqqEZ4Ye6jIPRtrwa9ifA" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1lWzl2fnOGrnXqqEZ4Ye6jIPRtrwa9ifA" target="_blank" rel="noopener noreferrer">(3.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1dTLKWvlx53kxaDsbT3keF3EmzgwfYir-" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1dTLKWvlx53kxaDsbT3keF3EmzgwfYir-" target="_blank" rel="noopener noreferrer">(576 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1m8DYu6y5BkolXkKqC9E8Lm77TpzpyeNR" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1m8DYu6y5BkolXkKqC9E8Lm77TpzpyeNR" target="_blank" rel="noopener noreferrer">(7.1 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/11iwPLTuBpKOHOzhktcuqAR3hXfh_7GvQ" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/11iwPLTuBpKOHOzhktcuqAR3hXfh_7GvQ" target="_blank" rel="noopener noreferrer">(944 KB)</a></td>
    <td class="tg-5hi3">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1_LvH-KVfBOW4ltSo8ERLEHWRb31OoAgW" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1_LvH-KVfBOW4ltSo8ERLEHWRb31OoAgW" target="_blank" rel="noopener noreferrer">(42 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1nJxVwgR35p8i0iR1sfcaiHpaXpLpCF8c" target="_blank" rel="noopener noreferrer">ntu_day_01 (41.5 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1f8G1Bntx7ynLeo5hVz8CQKkUdnNIFAVG" alt="ntu_day_01_gt" width="270" height="205"></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1E4oTZKaajNJA8KT9hcOsREU4If2mAHle" target="_blank" rel="noopener noreferrer">d435i</a><br><a href="https://drive.google.com/file/d/1E4oTZKaajNJA8KT9hcOsREU4If2mAHle" target="_blank" rel="noopener noreferrer">(13.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1u7nmGxrm0LJyIiYKPincojHcBOEw59kh" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1u7nmGxrm0LJyIiYKPincojHcBOEw59kh" target="_blank" rel="noopener noreferrer">(13.8 GB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1p7JCvUKh9BgKNPnt-SeC7oQgZ4S863KQ" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1p7JCvUKh9BgKNPnt-SeC7oQgZ4S863KQ" target="_blank" rel="noopener noreferrer">(542 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/127Rk2jX4I95CEWK1AOZRD9AQRxRVlWjY" target="_blank" rel="noopener noreferrer">os1_128</a><br><a href="https://drive.google.com/file/d/127Rk2jX4I95CEWK1AOZRD9AQRxRVlWjY" target="_blank" rel="noopener noreferrer">(13.8 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1FkEX5U8pE7XWzU70ni-0-DpGFFlIMcd-" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1FkEX5U8pE7XWzU70ni-0-DpGFFlIMcd-" target="_blank" rel="noopener noreferrer">(1 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1bBKRlzwG4v7K4mBmLAQzfwp_O6yOR0Ld" target="_blank" rel="noopener noreferrer">vn100</a><br><a href="https://drive.google.com/file/d/1bBKRlzwG4v7K4mBmLAQzfwp_O6yOR0Ld" target="_blank" rel="noopener noreferrer">(32 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1Cm5oHSq4OkWAzEUsq2qUMZA0Uq19QR_B" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1Cm5oHSq4OkWAzEUsq2qUMZA0Uq19QR_B" target="_blank" rel="noopener noreferrer">(54 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1Nt_khn7u8y3d1TIjY8Lyht2vI8qCG6Sy" target="_blank" rel="noopener noreferrer">ntu_day_02 (14.8 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1AhLaX-ViUqoRYM4UsYw1ZGwFVBIMhwio" alt="ntu_day_02_gt" width="270" height="205"></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1svtLKBcoxixWZjatwSP1MtJEmVTPE3wA" target="_blank" rel="noopener noreferrer">d435i</a><br><a href="https://drive.google.com/file/d/1svtLKBcoxixWZjatwSP1MtJEmVTPE3wA" target="_blank" rel="noopener noreferrer">(4.7 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1sfQdn6MGt4BsSx6PQtDdMZSiwfFcsihk" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1sfQdn6MGt4BsSx6PQtDdMZSiwfFcsihk" target="_blank" rel="noopener noreferrer">(4.9 GB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1y5vLjnwNI1Aj0uMp3HCsHm-HOfZbBC5h" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1y5vLjnwNI1Aj0uMp3HCsHm-HOfZbBC5h" target="_blank" rel="noopener noreferrer">(196 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1jDS84WvHCfM_L73EptXKp-BKPIPKoE0Z" target="_blank" rel="noopener noreferrer">os1_128</a><br><a href="https://drive.google.com/file/d/1jDS84WvHCfM_L73EptXKp-BKPIPKoE0Z" target="_blank" rel="noopener noreferrer">(5.0 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1a31zWxJK-OgqP6z4IV4WudF2DbcjYRxY" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1a31zWxJK-OgqP6z4IV4WudF2DbcjYRxY" target="_blank" rel="noopener noreferrer">(400 KB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1FHsJ1Hosn_j4m5KivJrdtECdFEj3Is0G" target="_blank" rel="noopener noreferrer">vn100</a><br><a href="https://drive.google.com/file/d/1FHsJ1Hosn_j4m5KivJrdtECdFEj3Is0G" target="_blank" rel="noopener noreferrer">(12 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1wo1rUuzqDkvFMhXJhx9fnNtn6uyh_F7z" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1wo1rUuzqDkvFMhXJhx9fnNtn6uyh_F7z" target="_blank" rel="noopener noreferrer">(25 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1IqB9k_5TQU4xVhQD060XB-T1ISORCeEE" target="_blank" rel="noopener noreferrer">ntu_day_10 (20.9 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1wXxrLMvshlvyQX7lU8_3BrCzhIjxUri7" alt="ntu_day_10_gt" width="270" height="205"></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1EyC3I7jIO-5ca5qrYxE4eoD1qTRKkOo5" target="_blank" rel="noopener noreferrer">d435i</a><br><a href="https://drive.google.com/file/d/1EyC3I7jIO-5ca5qrYxE4eoD1qTRKkOo5" target="_blank" rel="noopener noreferrer">(6.5 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1eGdELGvE2uCq063EexoK9E7I1hF3_Eke" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1eGdELGvE2uCq063EexoK9E7I1hF3_Eke" target="_blank" rel="noopener noreferrer">(6.8 GB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/10Pmtu6SlBGd2gzvu8OHm96eRVbR4lOTB" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/10Pmtu6SlBGd2gzvu8OHm96eRVbR4lOTB" target="_blank" rel="noopener noreferrer">(294 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1p18Fa5SXbVcCa9BJb_Ed8Fk_NRcahkCF" target="_blank" rel="noopener noreferrer">os1_128</a><br><a href="https://drive.google.com/file/d/1p18Fa5SXbVcCa9BJb_Ed8Fk_NRcahkCF" target="_blank" rel="noopener noreferrer">(7.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1eoW4cn-K78kUzjJu_ogtYWE4BIVR0f2l" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1eoW4cn-K78kUzjJu_ogtYWE4BIVR0f2l" target="_blank" rel="noopener noreferrer">(602 KB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/14IydATXlqbJ0333iNY7H-bFDBBBYF-nC" target="_blank" rel="noopener noreferrer">vn100</a><br><a href="https://drive.google.com/file/d/14IydATXlqbJ0333iNY7H-bFDBBBYF-nC" target="_blank" rel="noopener noreferrer">(18 MB)</a></td>
    <td class="tg-5hi3">-</td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1gi18OHqGDTNO-ZkRjP0_wJ5jizResVO-" target="_blank" rel="noopener noreferrer">ntu_night_04 (22.1 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1rjcBvUEX31C7tNT2MdNdkiVVDEzAVcVd" alt="ntu_night_04_gt" width="270" height="205"></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1Uwhwi41yzPeAWCOmhNJlcaLM1PI8x-nh" target="_blank" rel="noopener noreferrer">d435i</a><br><a href="https://drive.google.com/file/d/1Uwhwi41yzPeAWCOmhNJlcaLM1PI8x-nh" target="_blank" rel="noopener noreferrer">(6.7 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/13kmnVVPhTmOHJeuNu50A60x_bC5nchT5" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/13kmnVVPhTmOHJeuNu50A60x_bC5nchT5" target="_blank" rel="noopener noreferrer">(8.4 GB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1PlZMdVOMpJPxzdgb3uTDC4-REqmxQUXj" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1PlZMdVOMpJPxzdgb3uTDC4-REqmxQUXj" target="_blank" rel="noopener noreferrer">(266 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1k9olfETU3f3iq_9QenzEfjTpD56bOtaV" target="_blank" rel="noopener noreferrer">os1_128</a><br><a href="https://drive.google.com/file/d/1k9olfETU3f3iq_9QenzEfjTpD56bOtaV" target="_blank" rel="noopener noreferrer">(6.7 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1QTVHDloE-PBGf9nA8NRXsKB4NVN4r5gT" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1QTVHDloE-PBGf9nA8NRXsKB4NVN4r5gT" target="_blank" rel="noopener noreferrer">(561 KB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1dLvaCBmac-05QtPy-ZsiU6L5gY35Z_ii" target="_blank" rel="noopener noreferrer">vn100</a><br><a href="https://drive.google.com/file/d/1dLvaCBmac-05QtPy-ZsiU6L5gY35Z_ii" target="_blank" rel="noopener noreferrer">(16 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1jR4qC2WEANisd_c1b8UEc01rGYOxuOpP" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1jR4qC2WEANisd_c1b8UEc01rGYOxuOpP" target="_blank" rel="noopener noreferrer">(33 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1UGyFtPRjDiGDUDfq4iXHiPU1EzilF2HI" target="_blank" rel="noopener noreferrer">ntu_night_08 (31.9 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1MCc5hZKvmRJJ_7j29ClpJl79v0cCbjxq" alt="ntu_night_08_gt" width="270" height="205"></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/19sVbwKINJjHRWtbGZu-Sgxj4GHbAMZvR" target="_blank" rel="noopener noreferrer">d435i</a><br><a href="https://drive.google.com/file/d/19sVbwKINJjHRWtbGZu-Sgxj4GHbAMZvR" target="_blank" rel="noopener noreferrer">(8.0 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1FSDLGZzZtXibRwyLarjO6pF4FOgeQYC3" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1FSDLGZzZtXibRwyLarjO6pF4FOgeQYC3" target="_blank" rel="noopener noreferrer">(12.9 GB)</a></td>
    <td class="tg-5hi3">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1BjThXtxFt1pnqqE7Fq7Ytn0mPrQGZ427" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1BjThXtxFt1pnqqE7Fq7Ytn0mPrQGZ427" target="_blank" rel="noopener noreferrer">(427 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1BbtBDwT3sLCHCOFfZWeVVWbG72mWq8x8" target="_blank" rel="noopener noreferrer">os1_128</a><br><a href="https://drive.google.com/file/d/1BbtBDwT3sLCHCOFfZWeVVWbG72mWq8x8" target="_blank" rel="noopener noreferrer">(10.5 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1CsM-OieMxO11XgVTki31aIiGDFviSA84" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1CsM-OieMxO11XgVTki31aIiGDFviSA84" target="_blank" rel="noopener noreferrer">(823 KB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1oTUfLaQO9sUjesg6Bn3xbSZt3XgQqVRo" target="_blank" rel="noopener noreferrer">vn100</a><br><a href="https://drive.google.com/file/d/1oTUfLaQO9sUjesg6Bn3xbSZt3XgQqVRo" target="_blank" rel="noopener noreferrer">(25 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1U_7zuoTPC9QCHfeulPMIKw9e7C2i9W0r" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1U_7zuoTPC9QCHfeulPMIKw9e7C2i9W0r" target="_blank" rel="noopener noreferrer">(42 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1samHxI8NdM73uOtLT7KSPFbLppU1ffGy" target="_blank" rel="noopener noreferrer">ntu_night_13 (17.3 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1_AnDt9MEVmq-RRqL8Hb3eWZI4-uGQLPM" alt="ntu_night_13_gt" width="270" height="205"></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1q9p1wj9WsZS8xOFL9Uad9RKe-chfmahB" target="_blank" rel="noopener noreferrer">d435i</a><br><a href="https://drive.google.com/file/d/1q9p1wj9WsZS8xOFL9Uad9RKe-chfmahB" target="_blank" rel="noopener noreferrer">(5.5 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/13iEg1GRRqnyddGz4yVugflwK4Ayoy1DN" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/13iEg1GRRqnyddGz4yVugflwK4Ayoy1DN" target="_blank" rel="noopener noreferrer">(6.6 GB)</a></td>
    <td class="tg-5hi3">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1Qa9aSr58cJUAXjrgMqZ9P_Kv9d_z94M8" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1Qa9aSr58cJUAXjrgMqZ9P_Kv9d_z94M8" target="_blank" rel="noopener noreferrer">(200 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/17Fn_HRVwSEzQqXwkw0J3NnqxekUMjnYI" target="_blank" rel="noopener noreferrer">os1_128</a><br><a href="https://drive.google.com/file/d/17Fn_HRVwSEzQqXwkw0J3NnqxekUMjnYI" target="_blank" rel="noopener noreferrer">(5.0 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1ebR3PtgZ0SrmVhJSbqFh-0AGXif39ogH" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1ebR3PtgZ0SrmVhJSbqFh-0AGXif39ogH" target="_blank" rel="noopener noreferrer">(432 KB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1lru1JVyjfzM_QmctEzMtgD6ps8ib5xYs" target="_blank" rel="noopener noreferrer">vn100</a><br><a href="https://drive.google.com/file/d/1lru1JVyjfzM_QmctEzMtgD6ps8ib5xYs" target="_blank" rel="noopener noreferrer">(13 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1bI3Je2Py14zBXbNW8_tOAeKlFT9xWGid" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1bI3Je2Py14zBXbNW8_tOAeKlFT9xWGid" target="_blank" rel="noopener noreferrer">(24 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/19wgO-cuvhmZXxg24eMPrRH69GntI98PH" target="_blank" rel="noopener noreferrer">tuhh_day_02 (29.5 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="tuhh_day_02_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1T-eZ__o3h7Jctc0XXHfP86FlVQ_sYFHD" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1T-eZ__o3h7Jctc0XXHfP86FlVQ_sYFHD" target="_blank" rel="noopener noreferrer">(11.8 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1NQLfz_dWgECWxpCNljHVrrDUUXmR5lfo" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1NQLfz_dWgECWxpCNljHVrrDUUXmR5lfo" target="_blank" rel="noopener noreferrer">(11.8 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1n_ipXhXEX7RZSHyYrHjimcwA5ZuA7_3_" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1n_ipXhXEX7RZSHyYrHjimcwA5ZuA7_3_" target="_blank" rel="noopener noreferrer">(446 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1LErPETriJjLWhMBE5jvfpxoFujn0Z3cp" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1LErPETriJjLWhMBE5jvfpxoFujn0Z3cp" target="_blank" rel="noopener noreferrer">(5.5 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1Pga-z5b0yrsVsD-Q5ThZFmmkF9y-1P0R" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1Pga-z5b0yrsVsD-Q5ThZFmmkF9y-1P0R" target="_blank" rel="noopener noreferrer">(690 KB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1N3l-HskmBkta4OQVAneqnJhU29-6IeK8" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1N3l-HskmBkta4OQVAneqnJhU29-6IeK8" target="_blank" rel="noopener noreferrer">(31 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1E21qhp4J1BED41cF_2R0Df-_UOC8Rt2V" target="_blank" rel="noopener noreferrer">tuhh_day_03 (51.3 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="tuhh_day_03_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1raHVdY1F5tIkYc0y2DngEbZSAKNajxBI" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1raHVdY1F5tIkYc0y2DngEbZSAKNajxBI" target="_blank" rel="noopener noreferrer">(20.6 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1LnKeiYqo06tq1k-SuCd-3oC7s3gvnflj" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1LnKeiYqo06tq1k-SuCd-3oC7s3gvnflj" target="_blank" rel="noopener noreferrer">(20.5 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1S6Gcwn96SvpdzC6aMxrHB02umTSpzd4m" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1S6Gcwn96SvpdzC6aMxrHB02umTSpzd4m" target="_blank" rel="noopener noreferrer">(761 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1zTU8dnYNn1WRBGY-YkzqEiofH11vryTu" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1zTU8dnYNn1WRBGY-YkzqEiofH11vryTu" target="_blank" rel="noopener noreferrer">(9.4 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/18crbjWlLVZbo9C41LEIRvQ7Zc27UHrXe" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/18crbjWlLVZbo9C41LEIRvQ7Zc27UHrXe" target="_blank" rel="noopener noreferrer">(1 MB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/12SJQrHjFKNUMeoNuXNh7l0gd1w--B5Vl" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/12SJQrHjFKNUMeoNuXNh7l0gd1w--B5Vl" target="_blank" rel="noopener noreferrer">(52 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1Wby27hPjiWYfSHvULzIInChXxV8ISLVS" target="_blank" rel="noopener noreferrer">tuhh_day_04 (12.6 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="tuhh_day_04_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1_N9RYr7EauzCH97yu9XvO5bw-AeUd_t-" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1_N9RYr7EauzCH97yu9XvO5bw-AeUd_t-" target="_blank" rel="noopener noreferrer">(5.1 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1jLteGEXqN5yXf86WqiUBCaZrjcBIVPSa" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1jLteGEXqN5yXf86WqiUBCaZrjcBIVPSa" target="_blank" rel="noopener noreferrer">(5.1 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1_cihEpkuxN_BSkYI224D9d3ps7xjfdJW" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1_cihEpkuxN_BSkYI224D9d3ps7xjfdJW" target="_blank" rel="noopener noreferrer">(178 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1IFzZoEyqjboOwntyiPHTUxGcBndE2e9S" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1IFzZoEyqjboOwntyiPHTUxGcBndE2e9S" target="_blank" rel="noopener noreferrer">(2.2 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1pFahkNe_9-zQxNZ9sC86HvtJ-N7a7ou0" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1pFahkNe_9-zQxNZ9sC86HvtJ-N7a7ou0" target="_blank" rel="noopener noreferrer">(318 KB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1EToB3VXrxmoyPtdL1bnlFgG-fcegAIOt" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1EToB3VXrxmoyPtdL1bnlFgG-fcegAIOt" target="_blank" rel="noopener noreferrer">(12 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1FC9ckLRsJ48vvRPY2VJhQtFuT4qLIHo-" target="_blank" rel="noopener noreferrer">tuhh_night_07 (10.2 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="tuhh_night_07_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1lGauAFszLU5JzVuevKx1Sr6JFcmgASfI" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1lGauAFszLU5JzVuevKx1Sr6JFcmgASfI" target="_blank" rel="noopener noreferrer">(2.5 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1Id9WG_3Nk5agbut1dKFVxFsEJm-hXCGo" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1Id9WG_3Nk5agbut1dKFVxFsEJm-hXCGo" target="_blank" rel="noopener noreferrer">(2.3 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/10oblK7jfo-e5uDf94qRwwxMcKTxHmxTv" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/10oblK7jfo-e5uDf94qRwwxMcKTxHmxTv" target="_blank" rel="noopener noreferrer">(388 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1y1GJkaofleWVU8ZoUByGkmXkq2lwm-k-" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1y1GJkaofleWVU8ZoUByGkmXkq2lwm-k-" target="_blank" rel="noopener noreferrer">(4.9 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1NyEIGBa9f3VsqQSJBt8Wo-qCqffcam8E" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1NyEIGBa9f3VsqQSJBt8Wo-qCqffcam8E" target="_blank" rel="noopener noreferrer">(623 KB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1Ngy1_UXOfhjhwr-BEpG6Rsh1gi1rrMho" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1Ngy1_UXOfhjhwr-BEpG6Rsh1gi1rrMho" target="_blank" rel="noopener noreferrer">(28 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1hBPyw1fXcOGeW98JCLL2nmZ-TCKxhqvt" target="_blank" rel="noopener noreferrer">tuhh_night_08 (16.7 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="tuhh_night_08_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1ilQ4Npu0Y2WaSro4xJDcCqgk3iMSX4Bp" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1ilQ4Npu0Y2WaSro4xJDcCqgk3iMSX4Bp" target="_blank" rel="noopener noreferrer">(4.2 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1GaxDUF04_00x-qt_oYB78HxLjz3XrE9Y" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1GaxDUF04_00x-qt_oYB78HxLjz3XrE9Y" target="_blank" rel="noopener noreferrer">(4.0 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1p1BIv0cm96KybsnYp6aG7dFd1TvSi8Jl" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1p1BIv0cm96KybsnYp6aG7dFd1TvSi8Jl" target="_blank" rel="noopener noreferrer">(636 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/16t33lVBzbSxrtt0vFt-ztWAxiciONWTX" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/16t33lVBzbSxrtt0vFt-ztWAxiciONWTX" target="_blank" rel="noopener noreferrer">(7.9 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1wvsasGQgvuMeNg1QXeBzuLCq_rNvfGGV" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1wvsasGQgvuMeNg1QXeBzuLCq_rNvfGGV" target="_blank" rel="noopener noreferrer">(1 MB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1bDjyQLINKWBVOg_7Q1n1mooUfM3VifOu" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1bDjyQLINKWBVOg_7Q1n1mooUfM3VifOu" target="_blank" rel="noopener noreferrer">(44 MB)</a></td>
  </tr>
  <tr>
    <td class="tg-11ai"><a href="https://drive.google.com/drive/folders/1nEPiTXkVmLIhmBOVNpwSAEgnAXupnAxx" target="_blank" rel="noopener noreferrer">tuhh_night_09 (3.5 GB)</a></td>
    <td class="tg-11ai"><img src="https://drive.google.com/uc?id=1jNxIauPSM-bMhF0nffWFb7BhPe3fyr6w" alt="tuhh_night_09_gt" width="270" height="162"></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1VmHgEj6GI0mPhLOA-gJo1UG8G9FrM26c" target="_blank" rel="noopener noreferrer">d455b</a><br><a href="https://drive.google.com/file/d/1VmHgEj6GI0mPhLOA-gJo1UG8G9FrM26c" target="_blank" rel="noopener noreferrer">(607 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1mIp0weY6DPhdouJkqAiBIis2rYil5KJQ" target="_blank" rel="noopener noreferrer">d455t</a><br><a href="https://drive.google.com/file/d/1mIp0weY6DPhdouJkqAiBIis2rYil5KJQ" target="_blank" rel="noopener noreferrer">(634 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1-hZWGvZR0RmqKHehhjoQ44pkAhpCnktR" target="_blank" rel="noopener noreferrer">mid70</a><br><a href="https://drive.google.com/file/d/1-hZWGvZR0RmqKHehhjoQ44pkAhpCnktR" target="_blank" rel="noopener noreferrer">(176 MB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1_FsTTQe-NKvQ-1shlYNeG0uWqngA2XzC" target="_blank" rel="noopener noreferrer">os1_64</a><br><a href="https://drive.google.com/file/d/1_FsTTQe-NKvQ-1shlYNeG0uWqngA2XzC" target="_blank" rel="noopener noreferrer">(2.1 GB)</a></td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1eGRAqP5DpcIV7eAWawhaD5OCfZcJQlIG" target="_blank" rel="noopener noreferrer">ltpb</a><br><a href="https://drive.google.com/file/d/1eGRAqP5DpcIV7eAWawhaD5OCfZcJQlIG" target="_blank" rel="noopener noreferrer">(312 KB)</a></td>
    <td class="tg-s527">-</td>
    <td class="tg-vu6z"><a href="https://drive.google.com/file/d/1jVQTmFX2pnYNULU5CjbOVa6hp_7zQoez" target="_blank" rel="noopener noreferrer">vn200</a><br><a href="https://drive.google.com/file/d/1jVQTmFX2pnYNULU5CjbOVa6hp_7zQoez" target="_blank" rel="noopener noreferrer">(12 MB)</a></td>
  </tr>
</tbody>
</table>

# Quick use

Work in Progress

# Related works

Work in Progress

# Notes:

If you have some inquiry, please raise an [issue](https://github.com/mcdviral/mcdviral.github.io/issues) on github.

# Licence
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/) and is intended for non-commercial academic use.
If you are interested in using the dataset for commercial purposes please [contact us](mailto:aris.eee.ntu@gmail.com).
