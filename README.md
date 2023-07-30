# BulkMaterials_ML

In this project, we apply Gaussian process to in SKLEARN module to predict properties of bulk materials in energy conversion and catalytic applications. 

Goal: Predicting Bulk Modulus (Voigt Modulus) of materials

Major workflow: 
1. Import data from Material Project
2. Explore relevant dataset, e.g., Etot, dynamic stability, voigt modulus etc.
3. Split data into training and testing sets
4. Coulomb matrix fingerprint and Gaussian process
5. Kernal optimization
6. Find best feature for the ML model with discared unstable materials
