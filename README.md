# motor-test-report
---
This repository contains a set of tools for performing motor test by utilizing [dynamometer series 1520 from RCbenchmark](http://www.rcbenchmark.com/product/thrust-stand-1520/) and conducting performance report from data csv file which is generated by [RCbenchmark Chrome APP](https://chrome.google.com/webstore/detail/rcbenchmarkcom-gui/loaadjknlfcpljcickkiogkbmollildg) and [the custom step test script](./custom_step_test.js).

## custom_step_test.js
This file contains the script to perform a step test on target motor/propeller combination.

## report_gen.ipynb
This file reads through the csv file produced by the script and generates the performance report on the combination.