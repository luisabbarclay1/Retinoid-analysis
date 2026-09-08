# Retinoid Chemistry: Marketing Claims vs Molecular Reality


This project is an investigation into the deeper chemistry behind claims pushed at us from tactically eye-catching bottles promising to perfect our skin. The analysis is intended as a widely accessible demonstration of the gap between potentially misleading marketing language and the molecular realities. Skincare is an industry which will remain in high demand due to the almost inescapable rise of skin issues and the popularity of anti-aging culture. 

## What This Project Does

- Compares four vitamin A derivatives using RDKit to generate molecular structures, mechanisms and descriptors.

- Reviews two randomised clinical trials, extracting and evaluating their findings.

- Surveys five retinoid products sold by a British retailer (Boots), comparing the marketing claims against the chemistry.


## Key Findings

- Each conversion step on the 'Conversion Ladder' reduces the amount of active retinoic acid delivered. In a bioactivity experiment from one of the trials, 0.1% retinoic acid produced a larger receptor response than 0.4% retinol, despite being applied at a quarter of the concentration [1]. 

- Higher concentrations can compensate for those losses. A 1.1% precursor formulation showed no significant difference in photoaging scores against 0.02% tretinoin, with substantially less irritation [2].

- Concentration is therefore what matters most, yet two of the five products surveyed omitted this figure. 



## Contents

- `retinoid_analysis.ipynb`: The full analysis 
- `conversion_ladder.png`: Enzymatic conversion pathway
- `ester_prodrug.png`: The ester prodrug strategy
- `four_molecules.png`: The four retinoids displayed 
- `isomer_pair.png`: Tretinoin & Isotretinoin side by side 
- `receptor_activation.png`: Receptor response data from Kafi et al.

## Running It

- Requires Python 3 with the following packages:
```
pip install rdkit pandas matplotlib
```
- Open `retinoid_analysis.ipynb` and run all cells from the top.

## References

1. Kafi R, Kwak HSR, Schumacher WE, et al. Improvement of Naturally Aged Skin With Vitamin A (Retinol). *Arch Dermatol.* 2007;143(5):606–612. doi:10.1001/archderm.143.5.606

2. Chien AL, Kim DJ, Cheng N, et al. Biomarkers of Tretinoin Precursors and Tretinoin Efficacy in Patients With Moderate to Severe Facial Photodamage: A Randomized Clinical Trial. *JAMA Dermatol.* 2022;158(8):879–886. doi:10.1001/jamadermatol.2022.1891

## Link To Public Deployment on Stoichio

https://stoichio.onrender.com


