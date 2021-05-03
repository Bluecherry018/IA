# Kmeans Project

This project consists of the execution and validation of the unsupervised learning algorithm for clustering (K-means) studied in the discipline of Artificial Intelligence, taught by Prof. Dr. Heloisa de Arruda Camargo.

## Dataset

We used in the two stages of the project a data set called diagnosis.data with 8 variables, found in the UCI repository: https://archive.ics.uci.edu/ml/datasets/Acute+Inflammations

 - Temperature of patient {36C - 42C}
 - Ocurrence of nausea {yes - no}
 - Lumbar pain {yes - no}
 - Lrine pushing {yes - no}
 - Micturition pains {yes - no}
 - Burning of urethra {yes - no}
 - Inflammation of urinary bladder {yes - no}
 - Nephritis of renal pelvis origin {yes - no}

The attributes represent symptoms of patients that result in two diagnoses, Inflammation of urinary bladder and Nephritis of renal pelvis origin, we decided to use the diagnosis 'Nephritis of renal pelvis origin' as a target attribute.

After that we perform 2 steps:

Part 1 - Validation with external index (Adusted Rand Index)

Part 2 - Determining the best number of groups using the quadratic sum of the distances with internal index ("elbow" method)
