# movingload_beamanalysis
# Moving Load Beam Analysis

This project implements a Python program to analyze a simply supported beam subjected to two moving point loads using the concept of Influence Line Diagrams.

## 🔍 Problem Statement

Develop an algorithm to calculate:

- Maximum reaction at supports A and B
- Bending moment at point W1 = 0 m
- Shear force at mid-span (0.5L)
- Maximum shear force and bending moment, along with their locations

## 📥 Input Parameters

- `L` : Length of the beam (in meters)
- `W1` : First moving load (in kN)
- `W2` : Second moving load (in kN)
- `x` : Distance between the two loads (in meters)

## ✅ Output

The program prints:

- Maximum Reaction at A and B
- Bending Moment (BM_01)
- Shear Force (SF_01)
- Maximum Shear Force (SF_max)
- Maximum Bending Moment (BM_max)
- Their respective locations from support A

## 🧮 Tools and Libraries

- Python 3.x
- Standard input/output (no external libraries)

## 📄 Files

- `beam_analysis.py`: Main Python file with user input, logic, and output.
- `README.md`: Project overview and usage.
- `report.tex`: LaTeX report for documentation.

## 🚀 How to Run

```bash
python beam_analysis.py
