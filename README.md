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

There are 18 sequences captured in as rosbags compressed with bz2 method. We split the data into different bag based on the sensors so that user can freely select the combo that suits their interest.

**It is recommended that user reads through the [notes](Sensors.html) on each sensor to use the sensor data correctly.**

*(Note: Currently only ntu_day_01 and kth_day_09 sequences may be downloadable. Others are still under development.)*

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-glkf{color:#00E;font-weight:bold;text-align:left;text-decoration:underline;vertical-align:top}
.tg .tg-nrix{text-align:center;vertical-align:middle}
.tg .tg-p59o{color:#00E;text-align:center;text-decoration:underline;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1566px">
<colgroup>
<col style="width: 120px">
<col style="width: 160px">
<col style="width: 160px">
<col style="width: 160px">
<col style="width: 160px">
<col style="width: 160px">
<col style="width: 160px">
<col style="width: 160px">
<col style="width: 160px">
<col style="width: 80px">
</colgroup>
<thead>
  <tr>
    <th class="tg-wa1i">SeqID</th>
    <th class="tg-wa1i">D435i</th>
    <th class="tg-wa1i">D455 bottom</th>
    <th class="tg-wa1i">D455 top</th>
    <th class="tg-wa1i">Livox</th>
    <th class="tg-wa1i">Ouster</th>
    <th class="tg-wa1i">UWB</th>
    <th class="tg-wa1i">VN100</th>
    <th class="tg-wa1i">VN200</th>
    <th class="tg-amwm">GT</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1k5nQ81_1nA1Ng8IlQ1SghwBNmIUgbS0o">kth_day_06 (42.8 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1kZZhhqXT_pXLvLhlfGl5Ip4XpLCHF6_e">d455b (16.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1j_SfAzs3jZJOUmV-DA11Ixrln00pNb5x">d455t (16.1 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1X1fAdHPMXN5oYhtT6VsSZIppzTe9Ttda">mid70 (778 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1DHpRSoY5ysK1h2nRwks_6Sz-QZqERiXH">os1_64 (9.6 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1a2o-vQFK0vC0QqbXyM41BnzSNH9VkQ6N">ltpb (1 MB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1cf_dmcFAX9-5zxB8WcFVc3MaVNczEMqn">vn200 (56 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/17bE6-s3QjB7JJlmPYNLsJkTQgnHTeEyr">kth_day_09 (23.4 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1fGxxe5JGvkNC-BVyHeLdLfdTNkhTPC9i">d455b (7.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1yyrmxYYENBe5jmsfH6vONhvywB71Tzf8">d455t (7.1 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1LLEbZ244oicynIL4gjin7251ceo6IAgQ">mid70 (687 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1mhMpwr3NDYfUWL0dVAh_kCTTTLFen31C">os1_64 (8.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1yR9vVANK8jT5L35R3ilgI8ChDnA2nzhl">ltpb (1 MB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/16j2Ud99lrgkNtIlPQ_OV6caqZZc-bHA-">vn200 (48 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1bhGBi9DqoCxtqY3hbz666kCBuxVIwXQT">kth_day_10 (27.1 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1ww7LdYTnWgsQJ5YI4YgCkvdjIQBBn9Vp">d455b (10.0 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1X2Sbzm-zFKhE7MW9-dNJrv-2eyD2iFuh">d455t (9.9 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/19BiksWKakCinCq9FuYf203RY620R32cI">mid70 (525 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1NbOHfVaCZkXPz28VwLrWLfITXYn25odh">os1_64 (6.7 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1Nf5odmAA6sGTPXGBw-h4fR4_VoBDjwJ6">ltpb (876 KB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/13qyhDyrj6doa7s0cdbtF1e_Bh-erFMUv">vn200 (38 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1YZTvQ1QI86HW8C7Ifq6VFC02fQRtMMCw">kth_night_01 (43.5 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1xouzt8EHb9IlO_koXr_VsCwLh7qhUjyD">d455b (14.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1dQ1EgGcMePdEfXrtXyjVvyWgZSgVFNJz">d455t (17.9 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1jWp2THLV2v51a7APTUhbqVCH7z6Crtg_">mid70 (855 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1mbLMoTPdhUI9u-ZOYFQJOYgrcQJb3rvN">os1_64 (10.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1zIHjLy7iHt_VgjHVw5zmIXz6x_g4lMRB">ltpb (1 MB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1RMfF_DYxUkP6ImwCK039-qJpzbGKw_m7">vn200 (60 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1GJ2ZGsBBwiYY3DHk0XCE9cwV2s-xdM7a">kth_night_04 (14.9 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/15NtThX00mL6FIE_pvmoqkYTCisnZ9Ao2">d455b (3.2 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1HhsSyflVhO1JwOwgiVQv4f39kqRku4RK">d455t (3.2 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1T4rM9bnsOybm4C24pv4V8SHPOQQGEBMc">mid70 (650 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1SRMbAu1UyA4lJB4hZdmY-0mic-paGkKF">os1_64 (7.8 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1XLa2JYsJi5hzHb9trlvpuYot-M-aqCY6">ltpb (1 MB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/10KIUpaJIID293P3um8OfWWiiQ1NArj2o">vn200 (47 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1yK8xOTgZCiWCxcR_lVMKSfVwkgm5XYso">kth_night_05 (14.2 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1YD0s995Js23-en4NDvaHO_ifnfEnPdCq">d455b (3.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1lWzl2fnOGrnXqqEZ4Ye6jIPRtrwa9ifA">d455t (3.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1dTLKWvlx53kxaDsbT3keF3EmzgwfYir-">mid70 (576 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1m8DYu6y5BkolXkKqC9E8Lm77TpzpyeNR">os1_64 (7.1 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/11iwPLTuBpKOHOzhktcuqAR3hXfh_7GvQ">ltpb (944 KB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1_LvH-KVfBOW4ltSo8ERLEHWRb31OoAgW">vn200 (42 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1nJxVwgR35p8i0iR1sfcaiHpaXpLpCF8c">ntu_day_01 (41.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1E4oTZKaajNJA8KT9hcOsREU4If2mAHle">d435i (13.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1u7nmGxrm0LJyIiYKPincojHcBOEw59kh">d455b (13.8 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1p7JCvUKh9BgKNPnt-SeC7oQgZ4S863KQ">mid70 (542 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/127Rk2jX4I95CEWK1AOZRD9AQRxRVlWjY">os1_128 (13.8 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1FkEX5U8pE7XWzU70ni-0-DpGFFlIMcd-">ltpb (1 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1bBKRlzwG4v7K4mBmLAQzfwp_O6yOR0Ld">vn100 (32 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1Cm5oHSq4OkWAzEUsq2qUMZA0Uq19QR_B">vn200 (54 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1Nt_khn7u8y3d1TIjY8Lyht2vI8qCG6Sy">ntu_day_02 (14.8 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1svtLKBcoxixWZjatwSP1MtJEmVTPE3wA">d435i (4.7 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1sfQdn6MGt4BsSx6PQtDdMZSiwfFcsihk">d455b (4.9 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1y5vLjnwNI1Aj0uMp3HCsHm-HOfZbBC5h">mid70 (196 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1jDS84WvHCfM_L73EptXKp-BKPIPKoE0Z">os1_128 (5.0 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1a31zWxJK-OgqP6z4IV4WudF2DbcjYRxY">ltpb (400 KB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1FHsJ1Hosn_j4m5KivJrdtECdFEj3Is0G">vn100 (12 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1wo1rUuzqDkvFMhXJhx9fnNtn6uyh_F7z">vn200 (25 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1IqB9k_5TQU4xVhQD060XB-T1ISORCeEE">ntu_day_10 (20.9 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1EyC3I7jIO-5ca5qrYxE4eoD1qTRKkOo5">d435i (6.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1eGdELGvE2uCq063EexoK9E7I1hF3_Eke">d455b (6.8 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/10Pmtu6SlBGd2gzvu8OHm96eRVbR4lOTB">mid70 (294 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1p18Fa5SXbVcCa9BJb_Ed8Fk_NRcahkCF">os1_128 (7.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1eoW4cn-K78kUzjJu_ogtYWE4BIVR0f2l">ltpb (602 KB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/14IydATXlqbJ0333iNY7H-bFDBBBYF-nC">vn100 (18 MB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1gi18OHqGDTNO-ZkRjP0_wJ5jizResVO-">ntu_night_04 (22.1 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1Uwhwi41yzPeAWCOmhNJlcaLM1PI8x-nh">d435i (6.7 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/13kmnVVPhTmOHJeuNu50A60x_bC5nchT5">d455b (8.4 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1PlZMdVOMpJPxzdgb3uTDC4-REqmxQUXj">mid70 (266 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1k9olfETU3f3iq_9QenzEfjTpD56bOtaV">os1_128 (6.7 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1QTVHDloE-PBGf9nA8NRXsKB4NVN4r5gT">ltpb (561 KB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1dLvaCBmac-05QtPy-ZsiU6L5gY35Z_ii">vn100 (16 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1jR4qC2WEANisd_c1b8UEc01rGYOxuOpP">vn200 (33 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1UGyFtPRjDiGDUDfq4iXHiPU1EzilF2HI">ntu_night_08 (31.9 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/19sVbwKINJjHRWtbGZu-Sgxj4GHbAMZvR">d435i (8.0 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1FSDLGZzZtXibRwyLarjO6pF4FOgeQYC3">d455b (12.9 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1BjThXtxFt1pnqqE7Fq7Ytn0mPrQGZ427">mid70 (427 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1BbtBDwT3sLCHCOFfZWeVVWbG72mWq8x8">os1_128 (10.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1CsM-OieMxO11XgVTki31aIiGDFviSA84">ltpb (823 KB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1oTUfLaQO9sUjesg6Bn3xbSZt3XgQqVRo">vn100 (25 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1U_7zuoTPC9QCHfeulPMIKw9e7C2i9W0r">vn200 (42 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1samHxI8NdM73uOtLT7KSPFbLppU1ffGy">ntu_night_13 (17.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1q9p1wj9WsZS8xOFL9Uad9RKe-chfmahB">d435i (5.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/13iEg1GRRqnyddGz4yVugflwK4Ayoy1DN">d455b (6.6 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1Qa9aSr58cJUAXjrgMqZ9P_Kv9d_z94M8">mid70 (200 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/17Fn_HRVwSEzQqXwkw0J3NnqxekUMjnYI">os1_128 (5.0 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1ebR3PtgZ0SrmVhJSbqFh-0AGXif39ogH">ltpb (432 KB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1lru1JVyjfzM_QmctEzMtgD6ps8ib5xYs">vn100 (13 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1bI3Je2Py14zBXbNW8_tOAeKlFT9xWGid">vn200 (24 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/19wgO-cuvhmZXxg24eMPrRH69GntI98PH">tuhh_day_02 (29.5 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1T-eZ__o3h7Jctc0XXHfP86FlVQ_sYFHD">d455b (11.8 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1NQLfz_dWgECWxpCNljHVrrDUUXmR5lfo">d455t (11.8 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1n_ipXhXEX7RZSHyYrHjimcwA5ZuA7_3_">mid70 (446 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1LErPETriJjLWhMBE5jvfpxoFujn0Z3cp">os1_64 (5.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1Pga-z5b0yrsVsD-Q5ThZFmmkF9y-1P0R">ltpb (690 KB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1N3l-HskmBkta4OQVAneqnJhU29-6IeK8">vn200 (31 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1E21qhp4J1BED41cF_2R0Df-_UOC8Rt2V">tuhh_day_03 (51.3 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1raHVdY1F5tIkYc0y2DngEbZSAKNajxBI">d455b (20.6 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1LnKeiYqo06tq1k-SuCd-3oC7s3gvnflj">d455t (20.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1S6Gcwn96SvpdzC6aMxrHB02umTSpzd4m">mid70 (761 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1zTU8dnYNn1WRBGY-YkzqEiofH11vryTu">os1_64 (9.4 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/18crbjWlLVZbo9C41LEIRvQ7Zc27UHrXe">ltpb (1 MB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/12SJQrHjFKNUMeoNuXNh7l0gd1w--B5Vl">vn200 (52 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1Wby27hPjiWYfSHvULzIInChXxV8ISLVS">tuhh_day_04 (12.6 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1_N9RYr7EauzCH97yu9XvO5bw-AeUd_t-">d455b (5.1 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1jLteGEXqN5yXf86WqiUBCaZrjcBIVPSa">d455t (5.1 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1_cihEpkuxN_BSkYI224D9d3ps7xjfdJW">mid70 (178 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1IFzZoEyqjboOwntyiPHTUxGcBndE2e9S">os1_64 (2.2 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1pFahkNe_9-zQxNZ9sC86HvtJ-N7a7ou0">ltpb (318 KB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1EToB3VXrxmoyPtdL1bnlFgG-fcegAIOt">vn200 (12 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1FC9ckLRsJ48vvRPY2VJhQtFuT4qLIHo-">tuhh_night_07 (10.2 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1lGauAFszLU5JzVuevKx1Sr6JFcmgASfI">d455b (2.5 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1Id9WG_3Nk5agbut1dKFVxFsEJm-hXCGo">d455t (2.3 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/10oblK7jfo-e5uDf94qRwwxMcKTxHmxTv">mid70 (388 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1y1GJkaofleWVU8ZoUByGkmXkq2lwm-k-">os1_64 (4.9 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1NyEIGBa9f3VsqQSJBt8Wo-qCqffcam8E">ltpb (623 KB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1Ngy1_UXOfhjhwr-BEpG6Rsh1gi1rrMho">vn200 (28 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1hBPyw1fXcOGeW98JCLL2nmZ-TCKxhqvt">tuhh_night_08 (16.7 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1ilQ4Npu0Y2WaSro4xJDcCqgk3iMSX4Bp">d455b (4.2 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1GaxDUF04_00x-qt_oYB78HxLjz3XrE9Y">d455t (4.0 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1p1BIv0cm96KybsnYp6aG7dFd1TvSi8Jl">mid70 (636 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/16t33lVBzbSxrtt0vFt-ztWAxiciONWTX">os1_64 (7.9 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1wvsasGQgvuMeNg1QXeBzuLCq_rNvfGGV">ltpb (1 MB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1bDjyQLINKWBVOg_7Q1n1mooUfM3VifOu">vn200 (44 MB)</a></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-glkf"><a href="https://drive.google.com/drive/folders/1nEPiTXkVmLIhmBOVNpwSAEgnAXupnAxx">tuhh_night_09 (3.5 GB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1VmHgEj6GI0mPhLOA-gJo1UG8G9FrM26c">d455b (607 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1mIp0weY6DPhdouJkqAiBIis2rYil5KJQ">d455t (634 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1-hZWGvZR0RmqKHehhjoQ44pkAhpCnktR">mid70 (176 MB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1_FsTTQe-NKvQ-1shlYNeG0uWqngA2XzC">os1_64 (2.1 GB)</a></td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1eGRAqP5DpcIV7eAWawhaD5OCfZcJQlIG">ltpb (312 KB)</a></td>
    <td class="tg-nrix">-</td>
    <td class="tg-p59o"><a href="https://drive.google.com/file/d/1jVQTmFX2pnYNULU5CjbOVa6hp_7zQoez">vn200 (12 MB)</a></td>
    <td class="tg-baqh"></td>
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
