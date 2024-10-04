# Decision-Analytics
MSDS 460 Decision Analytics Course 

The Diet Problem Revisited (Version 11)

**Developed by:** Thomas W. Miller  
**Revised:** September 17, 2024

## Overview

Introduced by Stigler (1945) and discussed by Dantzig (1990), the diet problem is a classic problem in constrained optimization often used to introduce linear programming concepts. The diet problem has been studied extensively through the years (van Dooren 2018).

## Purpose

This project aims to construct a personalized diet using current recommended dietary allowances from the U.S. Food and Drug Administration, updated to account for recent research on sodium intake and health (Mente, O'Donnell, and Yusuf 2021). 

Interested in learning more about nutrition and healthy living? Check out [Nutrients](https://www.mdpi.com/journal/nutrients), an open-access journal.

## Nutritional Constraints

The constraints for this linear programming problem consider seven components of nutrition and their daily values, as shown in the following table:

| Component   | Max/Min  | Daily Amount and Measure         |
|-------------|----------|----------------------------------|
| Sodium      | Maximum  | 5,000 milligrams (mg)           |
| Energy      | Minimum  | 2,000 Calories (kilocalories, kcal) |
| Protein     | Minimum  | 50 grams (g)                    |
| Vitamin D   | Minimum  | 20 micrograms (µg)              |
| Calcium   | Minimum  | 1,300 milligrams (mg)              |
| Iron   | Minimum  | 18 milligrams (mg)           |
| Potassium   | Minimum  | 4,700 milligrams (mg)              |

## References
Stigler, G. J. (1945). The Cost of Subsistence.

Dantzig, G. B. (1990). Linear Programming: Foundations and Extensions.

van Dooren, C. (2018). The Diet Problem: A Historical Perspective.

Mente, A., O'Donnell, M. J., & Yusuf, S. (2021). Sodium Intake and Health: A Review.
