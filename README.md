# Advanced Python Final Project @ NYU Center for Data Science - Taxicab Analysis

Though waning in popularity, taxis still are one of the most common pay-per-ride transportation services in NYC.

- Fares fuel this service and are determined by set flat rates, metered fares, and tolls.
  - Flat rates can vary by destination, timing, and the new NYS Congestion Surcharge.
  - Metered fares vary on the distance, timing, and congestion of a trip.

With various new and old rules, rate and toll changes, and congestion variance, this becomes a complex pricing prediction challenge.

- Models just considering distance will still result in an RMSE of $5-$8.

## Problem Approach

1. Prep data to account for recent price changes.
2. Build a baseline model that can at least match $5-$8 RMSE.
3. Try different algorithms and features to improve RMSE.
4. Improve processing by parallelizing and optimizing functions/model.
5. Collect runtimes and RMSE at each step and visualize improvements.


In order to give a potential user an accurate prediction of their trip's fare, the error needs to be improved. We take a look at a previous Kaggle competition[^1] to test out some of the topics covered in the Advanced Python course. Our findings are contained in the [Final Presentation slides.](https://github.com/gcalbertini/pyCV/blob/main/Final%20Presentation.pptx)

[^1]: https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/overview
