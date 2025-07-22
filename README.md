# EDA_on_cars_specification

![automibles](https://github.com/user-attachments/assets/563a8de4-968a-4756-8fa0-77185e1be344)

The dataset From 1985 Ward's Automotive Yearbook

**Dataset:**
*  rows (cars)
* 26 columns (attributes)
* Mixed data types (numbers, text, and some missing values marked as ?)

**The datset columns**
1. symboling – Risk rating (-3 to 3)

2. normalized-losses – Normalized insurance loss (can be ?)

3. make – Car brand (e.g., alfa-romero, audi)

4. fuel-type – Gas or diesel

5. aspiration – Std or turbo

6. num-of-doors – Two or four doors

7. body-style – Sedan, hatchback, wagon, etc.

8. drive-wheels – fwd, rwd, 4wd

9. engine-location – front or rear

10. wheel-base – Wheelbase length

11. length, width, height – Dimensions

12. curb-weight – Car weight

13. engine-type – dohc, ohcv, etc.

14. num-of-cylinders – Four, six, etc.

15. engine-size – Displacement

16. fuel-system – mpfi, 2bbl, etc.

17. bore, stroke – Cylinder bore and stroke

18. compression-ratio – Compression ratio

19. horsepower – Engine horsepower

20. peak-rpm – Peak revolutions per minute

21. city-mpg, highway-mpg – Fuel efficiency

22. price – Car price (some missing).

**EDA Steps**

1. The dataset has no headers so defining a header
2. Analyse through .describe() method for all data types
3. Analyse through .info() method 
4. Replace the null values in this datset it is '?' so, first it converted into NaN using NumPy.Nan method.
5. Then empty data is removed from the dataset. (.dropna() method is used)
6. Converted some of the 'object' datatype columns into 'float64'
7. Several plots were made to analyse the data.
8. 
