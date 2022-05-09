# STAT 479 (Data Science Computing Project) Lyman Break Galaxy Assignment
## Parallel Computing in the Center for High Throughput Computing (CHTC) at UW-Madison
### Background
- A full-scale search using the CHTC for an undiscovered, gravitationally lensed, high-redshift Lyman-break Galaxy
- Pseudocode:
  - Search through the 2 million Lyman-break galaxies and compare to the preidentified cB58 Lyman-break Galaxy
  - Rescale the Flux for each spectrum
  - Use Correlation Coefficient between each test spectrum and cB58 as a distance metric
    - The most closely related spectrums will have the highest Correlation Coefficient distance metric
  - Compare the distance metric at each redshift between the test spectrum and cB58 to find the best match
  - Obtain the top 100 Test Spectrums and Graph the Best 10
### Report
- Folder containing final computational steps and graphs comparing the 10 best test spectrum and the cB58 Lyman-break galaxy
- Note: The code using the CHTC cannot be published to GitHub as this is a recurring course at UW-Madison
