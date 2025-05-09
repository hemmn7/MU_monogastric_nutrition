# University of Missouri Monograstric Nutrition and Physiology Lab
![image](https://github.com/user-attachments/assets/361904a3-301f-480c-adbc-5765d04ea35d)

# Microbial EC Number Database

A curated database linking enzyme commission (EC) numbers to specific carbohydrates degraded by microbial enzymes, organized by nutrient class and substrate specificity.
### Table of Contents
- [Background](#background)
- [File Structure](#file-structure)
- [Data Sources](#data-sources)
- [How to Use](#how-to-use)
- [Citation](#citation)
- [Contact](#contact)
## Background

This database was developed to support research in microbial carbohydrate metabolism by mapping carbohydrate-active enzymes to their respective substrates, based on EC numbers. This dataset is specifically curated for microbial enzymes and categorizes them by carbohydrate class, polysaccharide type, and known substrates.

The database was constructed using curated information from:
- [MetaCyc](https://metacyc.org/)
- [BRENDA](https://www.brenda-enzymes.org/)
## File Structure

The file contains the following parent classes:

- **Parent**: Broad classification of enzymes by nutrient class
- **Parent2**: Adds polysaccharide specificity (e.g., cellulose, starch)
- **Parent3**: Includes sub-polysaccharide context (e.g., amorphous cellulose)
- **Parent4**: Most specific classification, with known substrates and additional notes

A repeat column is included to denote if a subclass is repeated due to having multiple substrates that fall within the same parent class.
  
## Data Sources 

Data was manually curated from:
- MetaCyc (accessed March 24, 2025; Pathway Tools version 29.0)
- BRENDA (accessed March 24, 2025; Release 2024.1)

Enzymes were filtered to include:
- Microbial origin
- Clear EC number classification
- Known activity on specific carbohydrates

Substrate categories include dietary fiber (soluble/insoluble), starch, β-glucans, mannans, etc. Entries with unclear or non-specific activity were excluded.

## How to Use

This database is intended for use in:
- Annotating predicted 16s functionality 
- Building models of microbial carbohydrate metabolism
- Linking EC numbers to dietary carbohydrate degradation potential

Use Excel, Python, or R to parse the data.

## Citation

If you use this database, please cite:

Miller, H. E. and A. L. Petry (2025). *Microbial Carbohydrase EC Database* [Data set]. Zenodo. DOI: 10.5281/zenodo.15343851
## Contact

For questions or contributions, contact:

Monograstric Nutrition and Physiology Lab  
University of Missouri  
Email: swinenutrition@missouri.edu


