---
title: "CRAC-01 Mission & Link Budget"
date: 2022-09-14T00:00:00+08:00
draft: false
---

# CRAC-01 Mission Brief

CRAC-01 is a small satellite designed by Engineering Team of Chinese Radio Amateurs’ Club, Reger Technology and the Beijing No. 15th middle school students. The target is to have the amateur radio in the space and educational program with middle school students. The space amateur radio station will provide: 

* VHF telemetry downlink.

* UHF telecommand uplink.

* V/U NBFM transponder.

* X band image data downlink experiment. 

The X band image data downlink will be controlled through UHF public telecommand channel.

The educational mission includes:

* Fruit fly cartridge for the biology experiment in the space;

* The photographic captured on the orbit.


> ## Revision History
>
> * Initilized Version on 15-Sept-2022.






# Link Budget Caculation

## System Orbit Characteristics

CRAC-01 will fly on the LEO orbit, with

* 500km orbit apogee and perigee, 97.4 degree inclination
* TT&C with 5 degree elevation angle, 2078km slant range.
* V/U NBFM transponder, 15 degree elevation angle, 1408km slant range.
* Image/Data with 15 degree elevation angle, 1408km slant range.

## VHF Telemetry Downlink

| Parameter                                           | Value   | Units | Comments |
| --------------------------------------------------- | ------- | ----- | -------- |
| Frequency                                           | 145.995 | MHz   |          |
| Modulation Method                                   | GMSK    |       |          |
| Data Rate                                           | 9600    | bps   |          |
| System Allowed or Specified Bit-Error-Rate          | 1.0E-5  |       |          |
| Slant Range                                         | 2078    | Km    |          |
|                                                     |         |       |          |
| **Spacecraft**                                      |         |       |          |
| Spacecraft Transmitter Power Output                 | 27      | dBm   |          |
| Spacecraft EIRP                                     | -4      | dBW   |          |
| Path Loss                                           | 142.1   | dB    |          |
| Isotropic Signal Level at Ground Station            | -151.7  | dBW   |          |
|                                                     |         |       |          |
| **Ground Station (Eb/No Method)**                   |         |       |          |
| Ground Station Signal-to-Noise Power Density (S/No) | 58.4    | dBHz  |          |
| Telemetry System Eb/No for the Downlink             | 18.6    | dB    |          |
| Eb/No Threshold                                     | 10.1    | dB    |          |
| <u>System Link Margin</u>                           | 8.5     | dB    |          |
|                                                     |         |       |          |
| **Ground Station (SNR Method)**                     |         |       |          |
| Signal Power at Ground Station LNA Input            | -143.1  | dBW   |          |
| Ground Station Receiver Bandwidth                   | 16,000  | Hz    |          |
| Ground Station Receiver Noise Power                 | -159.5  | dBW   |          |
| Signal-to-Noise Power Ratio at Ground Station Rcvr  | 16.4    | dB    |          |
| System Required S/N                                 | 9.6     | dB    |          |
| <u>System Link Margin</u>                           | 6.8     | dB    |          |

## UHF Telecommand Uplink

| Parameter                                       | Value   | Units | Comments |
| ----------------------------------------------- | ------- | ----- | -------- |
| Frequency                                       | 435.915 | MHz   |          |
| Modulation Method                               | GMSK    |       |          |
| Data Rate                                       | 4800    | bps   |          |
| System Allowed or Specified Bit-Error-Rate      | 1.0E-5  |       |          |
| Slant Range                                     | 2078    | Km    |          |
|                                                 |         |       |          |
| **Ground Station**                              |         |       |          |
| Ground Station Transmitter Power Output         | 40      | dBm   |          |
| Ground Station EIRP                             | 18.2    | dBW   |          |
| Path Loss                                       | 151.6   | dB    |          |
| Isotropic Signal Level at Spacecraft            | -139.8  | dBW   |          |
|                                                 |         |       |          |
| **Spacecraft (Eb/No Method)**                   |         |       |          |
| Spacecraft Signal-to-Noise Power Density (S/No) | 63.2    | dBHz  |          |
| Command System Eb/No                            | 26.3    | dB    |          |
| Eb/No Threshold                                 | 10.6    | dB    |          |
| <u>System Link Margin</u>                       | 15.7    | dB    |          |
|                                                 |         |       |          |
| **Spacecraft (SNR Method)**                     |         |       |          |
| Signal Power at Spacecraft LNA Input            | -141.1  | dBW   |          |
| Spacecraft Receiver Bandwidth                   | 16,000  | Hz    |          |
| Spacecraft Receiver Noise Power                 | -162.2  | dBW   |          |
| Signal-to-Noise Power Ratio at Spacecraft Rcvr  | 21.1    | dB    |          |
| System Required S/N                             | 10.6    | dB    |          |
| <u>System Link Margin</u>                       | 10.5    | dB    |          |

## VHF NBFM Transponder Downlink

| Parameter                                           | Value  | Units | Comments |
| --------------------------------------------------- | ------ | ----- | -------- |
| Frequency                                           | 145.98 | MHz   |          |
| Modulation Method                                   | NBFM   |       |          |
| Analog Bandwidth                                    | 5000   | Hz    |          |
| System Allowed or Specified Bit-Error-Rate          | 1.0E-4 |       |          |
| Slant Range                                         | 1408   | Km    |          |
|                                                     |        |       |          |
| **Spacecraft**                                      |        |       |          |
| Spacecraft Transmitter Power Output                 | 27     | dBm   |          |
| Spacecraft EIRP                                     | -4     | dBW   |          |
| Path Loss                                           | 138.7  | dB    |          |
| Isotropic Signal Level at Ground Station            | -148.3 | dBW   |          |
|                                                     |        |       |          |
| **Ground Station (Eb/No Method)**                   |        |       |          |
| Ground Station Signal-to-Noise Power Density (S/No) | 61.8   | dBHz  |          |
| NBFM Transponder System Eb/No for the Downlink      | 27.9   | dB    |          |
| Eb/No Threshold                                     | 21     | dB    |          |
| <u>System Link Margin</u>                           | 6.9    | dB    |          |
|                                                     |        |       |          |
| **Ground Station (SNR Method)**                     |        |       |          |
| Signal Power at Ground Station LNA Input            | -139.7 | dBW   |          |
| Ground Station Receiver Bandwidth                   | 5,000  | Hz    |          |
| Ground Station Receiver Noise Power                 | -164.6 | dBW   |          |
| Signal-to-Noise Power Ratio at Ground Station Rcvr  | 24.8   | dB    |          |
| System Required S/N                                 | 20     | dB    |          |
| <u>System Link Margin</u>                           | 4.8    | dB    |          |

## UHF NBFM Transponder Uplink

| Parameter                                       | Value  | Units | Comments |
| ----------------------------------------------- | ------ | ----- | -------- |
| Frequency                                       | 435.9  | MHz   |          |
| Modulation Method                               | NBFM   |       |          |
| Analog Bandwidth                                | 5,000  | Hz    |          |
| System Allowed or Specified Bit-Error-Rate      | 1.0E-4 |       |          |
| Slant Range                                     | 1408   | Km    |          |
|                                                 |        |       |          |
| **Ground Station**                              |        |       |          |
| Ground Station Transmitter Power Output         | 40     | dBm   |          |
| Ground Station EIRP                             | 18.2   | dBW   |          |
| Path Loss                                       | 148.2  | dB    |          |
| Isotropic Signal Level at Spacecraft            | -136.4 | dBW   |          |
|                                                 |        |       |          |
| **Spacecraft (Eb/No Method)**                   |        |       |          |
| Spacecraft Signal-to-Noise Power Density (S/No) | 66.5   | dBHz  |          |
| NBFM Transponder System Eb/No                   | 32.6   | dB    |          |
| Eb/No Threshold                                 | 21     | dB    |          |
| <u>System Link Margin</u>                       | 11.6   | dB    |          |
|                                                 |        |       |          |
| **Spacecraft (SNR Method)**                     |        |       |          |
| Signal Power at Spacecraft LNA Input            | -137.7 | dBW   |          |
| Spacecraft Receiver Bandwidth                   | 5,000  | Hz    |          |
| Spacecraft Receiver Noise Power                 | -167.3 | dBW   |          |
| Signal-to-Noise Power Ratio at Spacecraft Rcvr  | 29.6   | dB    |          |
| System Required S/N                             | 20     | dB    |          |
| <u>System Link Margin</u>                       | 9.6    | dB    |          |

## X Band Image/Voice Data Downlink

| Parameter                                           | Value  | Units | Comments |
| --------------------------------------------------- | ------ | ----- | -------- |
| Frequency                                           | 10455  | MHz   |          |
| Modulation Method                                   | QPSK   |       |          |
| Data Rate                                           | 10     | Mbps  |          |
| System Allowed or Specified Bit-Error-Rate          | 1.0E-5 |       |          |
| Slant Range                                         | 1408   | Km    |          |
|                                                     |        |       |          |
| **Spacecraft**                                      |        |       |          |
| Spacecraft Transmitter Power Output                 | 30     | dBm   |          |
| Spacecraft EIRP                                     | 12.2   | dBW   |          |
| Path Loss                                           | 175.8  | dB    |          |
| Isotropic Signal Level at Ground Station            | -166   | dBW   |          |
|                                                     |        |       |          |
| **Ground Station (Eb/No Method)**                   |        |       |          |
| Ground Station Signal-to-Noise Power Density (S/No) | 83.5   | dBHz  |          |
| Image/Voice Data System Eb/No for the Downlink      | 13.5   | dB    |          |
| Eb/No Threshold                                     | 10.1   | dB    |          |
| <u>System Link Margin</u>                           | 3.4    | dB    |          |
|                                                     |        |       |          |
| **Ground Station (SNR Method)**                     |        |       |          |
| Signal Power at Ground Station LNA Input            | -119.7 | dBW   |          |
| Ground Station Receiver Bandwidth                   | 10     | MHz   |          |
| Ground Station Receiver Noise Power                 | -133.2 | dBW   |          |
| Signal-to-Noise Power Ratio at Ground Station Rcvr  | 13.5   | dB    |          |
| System Required S/N                                 | 9.6    | dB    |          |
| <u>System Link Margin</u>                           | 3.9    | dB    |          |

