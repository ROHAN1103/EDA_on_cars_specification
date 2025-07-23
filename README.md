# EDA_on_cars_specification

![automibles](https://github.com/user-attachments/assets/563a8de4-968a-4756-8fa0-77185e1be344)

The dataset From 1985 Ward's Automotive Yearbook

<h2>Dataset:</h2>

  1. rows (cars)
  2. 26 columns (attributes)
  3. Mixed data types (numbers, text, and some missing values marked as ?)

<h2>The datset columns</h2>

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
    
<h2>EDA Steps</h2>

1. The dataset has no headers so defining a header
2. Analyse through .describe() method for all data types
3. Analyse through .info() method 
4. Replace the null values in this datset it is '?' so, first it converted into NaN using NumPy.Nan method.
5. Then empty data is removed from the dataset. (.dropna() method is used)
6. Converted some of the 'object' datatype columns into 'float64'
7. Several plots were made to analyse the data.

<h2>Insights of analysis</h2>

1. Jaguar has the highest average car price i.e., 32250.0 and Chevrolet has the lowest.
2. Toyota has the most number of cars (31), Jaguar and Porsche has less i.e., 1 each.
3. Toyota as a leading car producer has the share of 19.50% in production.
4. There are only two fuel-type, Most of the cars are powered by gas (145) and remaining are powered by diesel (14)
5. There are 5 types of car body-types.
   * Sedan-79 cars
   * Hatchback-56 cars
   * Wagon-17 cars
   * Hardtop-5 cars
   * Convertible-2 cars
6. <b>There are 3 types of wheel-drives</b>

   <img width="562" height="432" alt="image" src="https://github.com/user-attachments/assets/24f08267-fd4a-48b1-8517-3573f309393a" />

    *Here you can visualise the car-types along with its body-type*

7. <b>Heat map</b>

    <img width="903" height="930" alt="image" src="https://github.com/user-attachments/assets/8e625d44-2f09-4729-9c1d-9ab8ef0a8e24" />

8. <b>Car companies manufacture cars with either 2-door or 4-door.</b>

    <img width="562" height="432" alt="image" src="https://github.com/user-attachments/assets/f59ced94-b45a-4aa7-9bea-9e52195a5d15" />

    *Here you can see body-style wise number of doors used in a car*

9. <b>Convertible cars are the costliest, whereas hatchback are cheapest comparitively.</b>

    <img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/10a03f81-fa3f-4e36-9fed-cb9d89c7a45e" />

10. <b>Visualizing car companies macturing cars with different body-types</b>

    <img width="562" height="547" alt="image" src="https://github.com/user-attachments/assets/319166e9-a0e8-420b-ac5d-17793ab36913" />

11. <b>Visualizing the relation of engine-size, horsepower and peak-rpm</b>

    <img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/9425fab0-6c2f-402e-bfd0-42f521aea36f" />

12. <b>Insights of top 3 car manufacturing companies</b>

    <img width="562" height="432" alt="image" src="https://github.com/user-attachments/assets/ef7ea6de-8e26-4f2a-b2c9-a1f605c846f2" />

    
