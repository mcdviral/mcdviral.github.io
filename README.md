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

At current stage, 18 sequences have been processed, 6 for each campus, 3 with day light and 3 in night time.

We also split the data into different bag based on the sensors. Users can freely select the combo that suits their interest. If you want download the whole sequence with all sensors, please click on the corresponding **SeqID**.

<!-- The bagfile are name-coded for easy reference as follows:

**\[campus\]\_\[day\|night\]\_\[sequence_id\]\_\[sensor\].bag** -->

**It is recommended that user reads through the [notes](Sensors.html) on each sensor to use the sensor data correctly.**

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-7btt{border-color:inherit;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>

<table class="tg" style="undefined;table-layout: fixed; width: 1027px">
<colgroup>
<col style="width: 72px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
<col style="width: 96px">
</colgroup>
<thead>
  <tr>
    <th class="tg-7btt">Campus</th>
    <th class="tg-7btt">SeqID (All Data)</th>
    <th class="tg-7btt">D435i</th>
    <th class="tg-7btt">D455 top</th>
    <th class="tg-7btt">D455 bottom</th>
    <th class="tg-7btt">VN100</th>
    <th class="tg-7btt">VN200</th>
    <th class="tg-7btt">Ouster</th>
    <th class="tg-7btt">Livox</th>
    <th class="tg-7btt">UWB</th>
    <th class="tg-7btt">Route</th>
    <th class="tg-7btt">GT</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" rowspan="6">ntu</td>
    <td class="tg-0pky">day_01 </td>
    <td class="tg-c3ow">d435i</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">vn100</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_128</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">day_08</td>
    <td class="tg-c3ow">d435i</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">vn100</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_128</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">day_10</td>
    <td class="tg-c3ow">d435i</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">vn100</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_128</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_04</td>
    <td class="tg-c3ow">d435i</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">vn100</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_128</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_08</td>
    <td class="tg-c3ow">d435i</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">vn100</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_128</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_13</td>
    <td class="tg-c3ow">d435i</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">vn100</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_128</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="6">kth</td>
    <td class="tg-0pky">day_06</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">day_09</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">day_10</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_01</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_04</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_05</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="6">tuhh</td>
    <td class="tg-0pky">day_02</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:400;font-style:normal">day_03</span></td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">day_04</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_07</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_08</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">night_09</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">d455t</td>
    <td class="tg-c3ow">d455b</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">vn200</td>
    <td class="tg-c3ow">os1_64</td>
    <td class="tg-c3ow">mid70</td>
    <td class="tg-c3ow">ltpb</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
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
