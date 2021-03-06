# PRECIP Radar Scan (TW)

This project visualizes the radar scanning strategy in the [PRECIP 2022](http://precip.org/) campaign for field oprators.

For standard usage, the [notebook](https://github.com/jhruppert/PRECIP_Radar_Scan_TW/blob/main/PRECIP_radar_scans_userdef.ipynb) pulls the latest radar image from CWB (https://www.cwb.gov.tw/V8/C/W/OBS_Radar.html), and plots the ranges and azimuths of the specified radar scans.

## How to run?
1. Choose the radars (S-Pol at Hsin-Chu or SEA-POL at Yonaguni, or both)
2. Specify the list of the scan azimuths and ranges.
3. Check out the output figure of the scans.
4. Repeat 2–3 to make final decision for the scan strategy.

## History:
* Rosimar Rios-Berrios's at NCAR – original developer for Pre-CIP 2021 campaign in Colorado.
* Hungjui Yu at CSU – modified for PRECIP 2022 campaign in Taiwan to retrieve CWB radar information.
* Jennifer DeHart at CSU – testing and correction for specific radars.
* James Ruppert at OU – updated plotting and added all the scan angle plans.

Last update - 20220701 - James Ruppert

## Example Figure:

![Example Figure](https://github.com/jhruppert/PRECIP_Radar_Scan_TW/blob/main/example.png)

