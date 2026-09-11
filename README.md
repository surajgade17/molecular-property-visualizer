# Molecular Property Visualizer 🧪

A Python tool for computing and visualizing molecular
properties of drug-like molecules using RDKit and Matplotlib.

## Project Information
- **Phase:** 2 - Data Science
- **Author:** Suraj Gade
- **GitHub:** github.com/surajgade17
- **Goal:** Cheminformatics & AI Drug Discovery

## What This Project Does
Takes a list of drug molecules, computes key molecular
properties using RDKit, checks Lipinski Rule of Five
drug-likeness criteria and creates visualization charts.

## Project Flow
1. Define drug molecule dataset with SMILES strings
2. Compute molecular properties using RDKit
3. Check Lipinski Rule of Five for each molecule
4. Create bar chart visualizations
5. Print complete analysis summary

## Molecules Analyzed
| Name | SMILES |
|------|--------|
| Ethanol | CCO |
| Aspirin | CC(=O)Oc1ccccc1C(=O)O |
| Benzene | c1ccccc1 |
| Caffeine | CN1C=NC2=C1C(=O)N(C(=O)N2C)C |
| Ibuprofen | CC(C)Cc1ccc(cc1)C(C)C(=O)O |

## Properties Computed
- **MW** — Molecular Weight (g/mol)
- **LogP** — Lipophilicity measure
- **HBD** — Hydrogen Bond Donors
- **HBA** — Hydrogen Bond Acceptors

## Lipinski Rule of Five
Drug-like molecules must satisfy:
- MW ≤ 500
- LogP ≤ 5
- HBD ≤ 5
- HBA ≤ 10

## Features
- Compute molecular properties using RDKit
- Check Lipinski Rule of Five drug-likeness
- Visualize MW and LogP distributions
- Generate summary statistics
- Save visualization as PNG file

## Tools Used
- Python 3
- RDKit
- Pandas
- Matplotlib
- Google Colab

## Sample Output

CHEMINFORMATICS SUMMARY

- Total molecules analyzed: 5
- Average molecular weight: 140.96 g/mol
- Average LogP: 1.01
- Lipinski PASS: 5
- Lipinski FAIL: 0

Visualization saved as: molecular_properties.png
Analysis completed successfully!

