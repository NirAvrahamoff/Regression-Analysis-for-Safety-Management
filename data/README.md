# Data

Three synthetic datasets provided for a university regression course. Column names were made consistent when the original pickle files were converted to CSV; the values are unchanged.

## machine_performance.csv (200 rows)

| Column | Description |
|---|---|
| temperature | Air temperature |
| humidity | Air humidity |
| performance | Machine performance score; higher is better |

## acid_classification.csv (120 rows)

| Column | Description |
|---|---|
| temp | Temperature of the residue |
| lumps | 1 if the residue contains lumps, 0 otherwise |
| hydrochloric_acid | 1 for hydrochloric acid, 0 for sulfuric acid |

## workplace_accidents.csv (10,000 rows, one per worker)

| Column | Description |
|---|---|
| age | Worker age in years |
| safety_score | Safety test score, 0 to 10 |
| factory | Ariel, Haifa, Jerusalem, Makeret_Batya or Tel_Aviv |
| chemical | Chemical the worker handles: Hydrochloric_acid or Sulfuric_Acid |
| years_in_factory | Years the worker has been in the factory, 1 to 10 |
| accidents | Total accidents over those years |
