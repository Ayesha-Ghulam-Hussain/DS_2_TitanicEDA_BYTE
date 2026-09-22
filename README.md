# \# Titanic Dataset EDA — AVIP 2026 (B.Y.T.E by Arithmatrix)

# 

# \## Dataset

# Source: https://www.kaggle.com/c/titanic/data

# Also available directly via: https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

# Extraction date: September 2026

# 

# \## Cleaning Steps

# \- \*\*Age\*\*: 177 missing values filled using median age per Title (Mr/Mrs/Miss/Master/Rare)

# \- \*\*Embarked\*\*: 2 missing values filled with the mode (most common port)

# \- \*\*Cabin\*\*: 687 missing values (77%) — converted to `Has\_Cabin` flag and `Deck` letter, then dropped

# \- \*\*Engineered features\*\*: `Title`, `FamilySize`, `IsAlone`, `AgeGroup`

# 

# \## Files

# \- `titanic\_eda.ipynb` — full analysis notebook

# \- `data/titanic\_raw.csv` — original dataset

# \- `data/titanic\_cleaned.csv` — cleaned dataset

# \- `images/` — exported charts

# 

# \## Charts

# !\[Survival by Class and Gender](images/survival\_by\_class\_gender.png)

# !\[Age Distribution](images/age\_distribution.png)

# !\[Correlation Heatmap](images/correlation\_heatmap.png)

# 

# \## Key Findings

# \- Women survived at 74.2% vs 18.9% for men

# \- 1st class survival was 63.0% vs 24.2% for 3rd class

# \- Children had the highest survival rate (57.5%) of any age group

# \- Passengers traveling alone survived less often (30.4%) than those with family (50.6%)

# 

# \## Conclusion

# Survival was driven primarily by gender, passenger class, and age, consistent with a 

# "women and children first" evacuation policy that also favored wealthier passengers. 

# A natural next step would be training a classification model using these features.

