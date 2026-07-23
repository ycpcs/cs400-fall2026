---
layout: default
title: RevMetrix Project
---

This is the web page for the RevMetrix Project for CS 400 Fall 2026 at [York College of Pennsylvania](http://www.ycp.edu).  All information specifically related to the RevMetrix Project will be posted here.

## Links

* [CS400-Fa25 Website](../../index.html)
* [Schedule](schedule.html)

## RevMetrix Project Description
Here are links to the previous research that Professor Hake conducted as part of his Master's Theses.

[RevMetrix MEng ESci Thesis](Hake-MEngESci-Masters-Thesis.pdf)

[RevMetrix MEng ESci Final Presentation](Hake-MEngESci-Masters-Defense-Presentation.pdf)

Here is a set of raw data from an actual bowling session.  There are two versions:

1) A [text version](./resources/Shots(0-19)-Suburban(8-29-10).txt) that contains the EEPROM contents, as well as a CSV extraction of the raw data from those EEPROM contents.

2) An [Excel Spreadsheet](./resources/Shots(0-19)-Suburban(8-29-10).xlsx) that also contains graphs of the extracted raw data for each shot in the session.

3) An [Updated Excel Spreadsheet](./resources/Shots(0-19)-Suburban(8-29-10)-BallRecord00002-annotated.xlsx) that contains annotation explaining the various components of the raw data.  A second page has been added for Ball Record 00002 that contains the actual 32-bit RTC (Real Time Clock) time stamps for all of the ADXL Pages, the Light Pages, and the SmartDot Events to be sent to the phone application.  The SmartDot Event time stamps can be used to send event signals via BLE in real time (during simulation) from the SmartDot simulator to the phone application.  For Ball Record 00002, all of the individual ADXL and Light sample time stamps have been recalculated based on the actual RTC captures for each page.  You can use these RTC time stamps to generate the exact time stamp values captured in the raw data when running the simulator.  Please look in the notes for the cells for additional information.  

## News

[General CS400 Fall 2025 News](../../index.html)