# Calibration System

## Description
Python scripts used to calibrate voltage and current measurements.

## Files
- VoltageCalibration.py
- CurrentCalibration.py

## Purpose
- Reduce measurement error
- Improve system accuracy

## Method
- Compare measured vs actual values
- Apply correction formula

## Requirements
- Python 3.x or Colab
- numpy
- matplotlib

## Process
Current Calibration

First, pass a current through a resistor and verify that it falls within our measurable range, then record the supplied current value. Next, apply the same current to our designed circuit and measure the corresponding output voltage. Convert this measured voltage into a digital value (ADC value). Repeat this process by varying the supply current to obtain several readings. Finally, derive a mathematical function (curve fitting) based on these readings and add that function to the calibration code in main.c.

Voltage Calibration

First, apply a known voltage and verify that it is within the measurable range, then record the supplied voltage value. Next, apply the same voltage to our designed circuit and measure the resulting output voltage. Convert this measured value into a digital value. Repeat this process by varying the supply voltage to gather multiple readings. Based on these readings, create a mathematical function and integrate it into the calibration code within main.c.
